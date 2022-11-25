<script>
export default{
 data: function(){
  return {
   name: "",
   price: "",
  }
},
methods: {
  addProduct(e){
    e.preventDefault() 
    alert("thanks alot" +" " +this.name + " " +" I am costed" + this.price);
  }
} 
}
</script>
<template>
<main> 

   
 
<form v-on:submit="addProduct">
  <input type="text" v-model="name" placeholder=" Name" >
  <input type="number" v-model="price" placeholder="Price">
  <button type="submit">submit</button>
</form>
</main>

</template>