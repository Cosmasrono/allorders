<template>
<main class="">
    <div class="flex gap-5 justify-center items-center" >
    <input type="radiobutton" id="radiobutton" class="w-4 h-4 text-blue-600 bg-gray-100 rounded border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600" v-model="picked">Landlord<br>
    <label for="radiobutton" class="sr-only">radiobutton</label>
    <input type="radiobutton" id="radiobutton"  class="w-4 h-4 text-blue-600 bg-gray-100 rounded border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600" v-model="picked" >Argency
    <label for="radiobutton" class="sr-only">radiobutton</label>
        <button type="submit" id="radio" class="p-3 bg-green-600">Submit</button>
        <span class="">picked:{{picked}}</span>
    </div>
    <a href="sms:254757450716?body=Hello Amohan,,i need your services"><button class="flex justify-center items-center p-5 ml-80 bg-green-400 rounded-md hover:scale-75">Inquire</button></a>

</main>
</template>


<script>
export default{
    data:function(){
        return{
            picked:"",
            

        }
    },
        methods :  {
      
    }
  }

</script>