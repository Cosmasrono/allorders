<script setup>
 import tableVue from '../components/table.vue';
</script>

<template>
  <main>
    hello this is an accomadation platform wherre you can find your desired house online without fear or favour you will have what you have asked
    <div class=" md:flex-col mb-52  grid  grid-rows-2 md:grid-rows-2 md:grid-cols-2 lg:grid-cols-2 grid-cols-1 items-center justify-center gap-4 mx-auto container">
              <div class="flex justify-center mx-auto items-center">
                  <img src="../assets/one.webp"   class=" h-80 w-80 rounded-md" alt="">
                  <a href="about" ><button class=" rounded-md m-5 p-5 bg-green-500 text-white">Accomodate me</button></a>
              </div>
              <div class="flex justify-center mx-auto items-center ">
                  <img src="../assets/two.jpg"   class=" h-80 w-80 rounded-md" alt="">
                  <a href="about/" ><button class=" rounded-md m-5 p-5 bg-green-500 text-white ">Accomodate me</button></a>
              </div>
              <div class=" flex justify-center mx-auto items-center">
                  <img src="../assets/three.jpg"   class=" h-80 w-80 rounded-md"  >
                  <a href="about" > <button class=" rounded-md  m-5 p-5 bg-green-500 text-white ">Accomodate me</button></a>
              </div>
              <div class=" flex justify-center mx-auto items-center">
                  <img src="../assets/four.webp"  class=" h-80 w-80 rounded-md"  alt="">
                  <a href="about" >  <button class=" rounded-md m-5 p-5 bg-green-500 text-white ">Accomodate me</button></a>
              </div>
              <div class=" flex justify-center mx-auto items-center">
                  <img src="../assets/ten.jpg"  class=" h-80 w-80 rounded-md"  alt="">
                  <a href="about" >   <button class=" rounded-md m-5 p-5 bg-green-500  text-white">Accomodate me</button></a>
              </div>
              <div class=" flex justify-center mx-auto items-center">
                  <img src="../assets/five.webp"  class=" h-80 w-80 rounded-md"  alt="">
                  <a href="/about" > <button class=" rounded-md m-5 p-5 bg-green-500 text-white">Accomodate me</button></a>
              </div>
              <div class="flex justify-center mx-auto items-center ">
                  <img src="../assets/six.jpg"   class=" h-80 w-80 rounded-md" alt="">
                  <a href="/about" >  <button class="rounded-md  m-5 p-5 bg-green-500 text-white ">Accomodate me</button></a>
              </div>
    
            <div class=" flex justify-center mx-auto items-center "> 
                 <img src="../assets/lepen.jpg" alt="" class=" h-80 w-80 rounded-md">  
                 <a href="/about" >  <button class="  rounded-md m-5 p-5 bg-green-500 text-white hover:inset-1">Accomodate me</button></a>
                </div>
                  </div>
              
      <p class=" bg-white flex flex-row"><br>
           </p>  
    
   <tableVue/>





    <footer class=" mt-20 fixed bottom-0 left-0 z-20 p-4 w-full bg-white border-t border-gray-200 shadow md:flex md:items-center md:justify-between md:p-6 dark:bg-gray-800 dark:border-gray-600">
     
    <ul class="flex flex-wrap items-center mt-3 text-sm text-gray-500 dark:text-gray-400 sm:mt-0">
        <li>
            <a href="#" class="mr-4 hover:underline md:mr-6 ">About</a>
        </li>
        <li>
            <a href="#" class="mr-4 hover:underline md:mr-6">Privacy Policy</a>
        </li>
        <li>
            <a href="#" class="mr-4 hover:underline md:mr-6">Licensing</a>
        </li>
        <li>
            <a href="#" class="hover:underline">Contact</a>
        </li>
    </ul>
    <span class="text-sm sm:text-center text-yellow-600">©cossi wing001@2022 . All Rights Reserved.
        </span>
</footer>
  </main>
</template>
