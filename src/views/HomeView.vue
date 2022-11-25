<script setup>
 import tableVue from '../components/table.vue';
</script>

<template>
  <main>
   <div class="flex flex-col md:flex-row">
      <img src="../assets/four.webp" alt="" class=""> 
      <div class="flex flex-col justify-center items-center p-3 mx-auto max-w-lg"> 
        <span class="text-lg text-yellow-500 md:text-3xl">Trust us for better tomorrow </span>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Alias consequuntur odit cumque sit temporibus architecto, placeat hic eligendi neque. Lauda
          ntium cum nobis praesentium eos est unde dignissimos vel suscipit maiores? </p>
        </div>
      </div>
  
    <h1 class="ml-20 text-lg text-yellow-500 md:text-3xl"><span class="">The Nairobi Apartments</span></h1>

    <div class="container grid grid-cols-1 grid-rows-2 gap-4 justify-center items-center mx-auto mb-10 md:flex-col md:grid-rows-2 md:grid-cols-2 lg:grid-cols-3">
              <div class="flex justify-center items-center mx-auto">
                <div class="">
             <h1> Rongai Apartments  <span class="text-yellow-500"> Rent:Ksh.9000</span></h1>
                  <img src="../assets/one.webp"   class="w-80 h-80 rounded-md" alt="">
                   <button class="p-5 m-5 ml-20 text-white bg-green-500 rounded-md">Accomodate me</button> 
              </div>
              
            </div>
              <div class="flex justify-center items-center mx-auto">
                <div class="">
             <h1> Ngara Road Apartments  <span class="text-yellow-500"> Rent:Ksh.6000</span></h1>
                  <img src="../assets/two.jpg"   class="w-80 h-80 rounded-md" alt="">
                   <button class="p-5 m-5 ml-20 text-white bg-green-500 rounded-md">Accomodate me</button> 
              </div>
              </div>
              <div class="flex justify-center items-center mx-auto">
                <div class="">
             <h1> Eastleigh Apartments  <span class="text-yellow-500"> Rent:Ksh.7000</span></h1>
                  <img src="../assets/three.jpg"   class="w-80 h-80 rounded-md"  >
                    <button class="p-5 m-5 ml-20 text-white bg-green-500 rounded-md">Accomodate me</button> 
              </div>
              </div>
              <div class="flex justify-center items-center mx-auto">
                <div class="">
             <h1> Ngong Hills Apartments  <span class="text-yellow-500"> Rent:Ksh.5000</span></h1>
                  <img src="../assets/four.webp"  class="w-80 h-80 rounded-md"  alt="">
                     <button class="p-5 m-5 ml-20 text-white bg-green-500 rounded-md">Accomodate me</button> 
              </div>
              </div>
              <div class="flex justify-center items-center mx-auto">
                <div class="">
             <h1> Kamukunji Apartments  <span class="text-yellow-500"> Rent:Ksh.10000</span></h1>
                  <img src="../assets/ten.jpg"  class="w-80 h-80 rounded-md"  alt="">
                      <button class="p-5 m-5 ml-20 text-white bg-green-500 rounded-md">Accomodate me</button> 
              </div>
              </div>
              
              <div class="flex justify-center items-center mx-auto">
                <div class="">
             <h1> Langat Apartments  <span class="text-yellow-500"> Rent:Ksh.13000</span></h1>
                  <img src="../assets/five.webp"  class="w-80 h-80 rounded-md"  alt="">
                    <button class="p-5 m-5 ml-20 text-white bg-green-500 rounded-md">Accomodate me</button> 
              </div>
              </div>
              <div class="flex justify-center items-center mx-auto">
                <div class="">
             <h1> kwa ken Apartments  <span class="text-yellow-500"> Rent:Ksh.4000</span></h1>
                  <img src="../assets/six.jpg"   class="w-80 h-80 rounded-md" alt="">
                     <button class="p-5 m-5 ml-20 text-white bg-green-500 rounded-md">Accomodate me</button> 
              </div>
              </div>
              <div class="flex justify-center items-center mx-auto">
                <div class="">
             <h1> kwa ken Apartments  <span class="text-yellow-500"> Rent:Ksh.4000</span></h1>
                  <img src="../assets/six.jpg"   class="w-80 h-80 rounded-md" alt="">
                     <button class="p-5 m-5 ml-20 text-white bg-green-500 rounded-md">Accomodate me</button> 
              </div>
              </div>
    
    
            <div class="flex justify-center items-center mx-auto"> 
                <div class="">
             <h1> kwa ken Apartments  <span class="text-yellow-500"> Rent:Ksh.4000</span></h1>
                 <img src="../assets/lepen.jpg" alt="" class="w-80 h-80 rounded-md">  
                  <button class="p-5 m-5 ml-20 text-white bg-green-500 rounded-md hover:inset-1">Accomodate me</button> 
                </div>
                  </div>
                  </div>
    <!--           
      <p class="flex flex-row bg-white"><br>
           </p>  --> 
    
   <tableVue/>





    <footer class="fixed bottom-0 left-0 p-4 w-full border-t border-gray-200 shadow bg-slate-800 md:flex md:items-center md:justify-between md:p-6 dark:bg-gray-800 dark:border-gray-600">
    <ul class="flex flex-wrap items-center text-sm text-gray-500 dark:text-gray-400 sm:mt-0">
        <li>
            <a href="#" class="mr-4 hover:underline md:mr-6"> </a>
        </li>
        <li>
            <a href="#" class="mr-4 hover:underline md:mr-6">Privacy Policy </a>
        </li>
        <li>
            <a href="#" class="mr-4 hover:underline md:mr-6">Licensing </a>
        </li>
        <li>
            <a href="#" class="hover:underline">Contact </a>
        </li>
    </ul>
    <span class="text-sm text-yellow-600 sm:text-center">©cossi wing001@2022 . All Rights Reserved.
        </span>
</footer>
  </main>
</template>
