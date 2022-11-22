<template>

    <div class="overflow-x-auto relative shadow-md sm:rounded-lg">
        <table class="w-full text-sm text-left text-gray-500 dark:text-gray-400">
            <thead class="text-xs text-gray-700 uppercase bg-gray-50 dark:bg-gray-700 dark:text-gray-400">
                <tr>
                    <th scope="col" class="p-4">
                        <!-- <div class="flex items-center">
                            <input id="checkbox" type="checkbox" class="w-4 h-4 text-blue-600 bg-gray-100 rounded border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600">
                            <label for="checkbox-all-search" class="sr-only">checkbox</label>
                        </div> -->
                    </th>
                    <th scope="col" class="py-3 px-6">
                        accomodation  name
                    </th>
                    <th scope="col" class="py-3 px-6">
                        Color
                    </th>
                    <th scope="col" class="py-3 px-6">
                        Category
                    </th>
                     <th scope="col" class="py-3 px-6">
                    </th> 
                    <th scope="col" class="py-3 px-6">
                        Availability
                    </th>
                    <th scope="col" class="py-3 px-6">
                        Price
                    </th>
                    <th scope="col" class="py-3 px-6">
                    </th> 
                    <th scope="col" class="py-3 px-6">
                        Action
                    </th>
                </tr>
            </thead>
            <tbody>
                <tr class="bg-white border-b dark:bg-gray-800 dark:border-gray-700 hover:bg-gray-50 dark:hover:bg-gray-600" v-for="accomodate in accomodations" :key="accomodate">
                    <td class="p-4 w-4">
                        <div class="flex items-center">
                            <input type="radiobutton" id="radiobutton"  class="w-4 h-4 text-blue-600 bg-gray-100 rounded border-gray-300 focus:ring-blue-500 dark:focus:ring-blue-600 dark:ring-offset-gray-800 focus:ring-2 dark:bg-gray-700 dark:border-gray-600"  v-model="checkedNames">
                            <label for="radiobutton" class="sr-only">checkbox</label>
                        </div>
                    </td>
                    <th scope="row" class="py-4 px-6 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                      {{accomodate.bedroom}}
                    </th>
                    <td class="py-4 px-6">
                        {{accomodate.color}}
                    </td>
                    <td class="py-4 px-6">
                        {{accomodate.type}}
                    </td>
                    <td class="py-4 px-6">
                    </td>
                    <td class="py-4 px-6">
                        {{accomodate.status}}
                    </td>
                    <td class="py-4 px-6">
                      {{accomodate.price}}
                    </td>
                     <td class="py-4 px-6">
                    </td> 
                    <td class="flex items-center py-4 px-6 space-x-3">
                      <button type="submit" @click.stop.prevent="submit()">Submit</button>
                    </td>
                </tr>
                 
            </tbody>
        </table>
    </div>
    
    </template>
    
    <script>
    export default{
      data(){
        return{
          accomodations:[
            {bedroom:' 3 bedroom',color:"silver", price:"5000", type:"laptop",status:"yes",desc:"  water:Ksh.1000 electrcity:ksh.3000 general:Ksh.30000"},
            {bedroom:' 2 bedroom',color:"silver", price:"5000", type:"laptop",status:"yes",desc:"  water:Ksh.1000 electrcity:ksh.3000 general:Ksh.30000"},
            {bedroom:' 1 bedroom',color:"silver", price:"5000", type:"laptop",status:"yes",desc:"  water:Ksh.1000 electrcity:ksh.3000 general:Ksh.30000"},
            {bedroom:' bedsitter',color:"silver", price:"5000", type:"laptop",status:"yes",desc:"  water:Ksh.1000 electrcity:ksh.3000 general:Ksh.30000"},
            {bedroom:' singleroom',color:"silver", price:"5000", type:"laptop",status:"yes",desc:"  water:Ksh.1000 electrcity:ksh.3000 general:Ksh.30000"}
          ]
        }
      },
      methods: {
        submit(){
           
     this.$router.push('/about') 
        }
    }
    }
      
    </script>