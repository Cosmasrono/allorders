<script setup>
 import tableVue from '../components/table.vue';
</script>

<template>
  <main>
    <h1 class=" flex items-center justify-center text-2xl">The Nairobi Apartments</h1>

    <div class=" md:flex-col mb-52  grid  grid-rows-2 md:grid-rows-2 md:grid-cols-2 lg:grid-cols-2 grid-cols-1 items-center justify-center gap-4 mx-auto container">
              <div class="flex justify-center mx-auto items-center">
                <div class="">
             <h1> Rongai Apartments  <span class=" text-yellow-500"> Rent:Ksh.9000</span></h1>
                  <img src="../assets/one.webp"   class=" h-80 w-80 rounded-md" alt="">
                  <a href="about" ><button class=" ml-20 rounded-md m-5 p-5 bg-green-500 text-white">Accomodate me</button></a>
              </div>
            </div>
              <div class="flex justify-center mx-auto items-center ">
                <div class="">
             <h1> Ngara Road Apartments  <span class=" text-yellow-500"> Rent:Ksh.6000</span></h1>
                  <img src="../assets/two.jpg"   class=" h-80 w-80 rounded-md" alt="">
                  <a href="about/" ><button class=" ml-20 rounded-md m-5 p-5 bg-green-500 text-white ">Accomodate me</button></a>
              </div>
              </div>
              <div class=" flex justify-center mx-auto items-center">
                <div class="">
             <h1> Eastleigh Apartments  <span class=" text-yellow-500"> Rent:Ksh.7000</span></h1>
                  <img src="../assets/three.jpg"   class=" h-80 w-80 rounded-md"  >
                  <a href="about" > <button class="ml-20 rounded-md  m-5 p-5 bg-green-500 text-white ">Accomodate me</button></a>
              </div>
              </div>
              <div class=" flex justify-center mx-auto items-center">
                <div class="">
             <h1> Ngong Hills Apartments  <span class=" text-yellow-500"> Rent:Ksh.5000</span></h1>
                  <img src="../assets/four.webp"  class=" h-80 w-80 rounded-md"  alt="">
                  <a href="about" >  <button class=" ml-20 rounded-md m-5 p-5 bg-green-500 text-white ">Accomodate me</button></a>
              </div>
              </div>
              <div class=" flex justify-center mx-auto items-center">
                <div class="">
             <h1> Kamukunji Apartments  <span class=" text-yellow-500"> Rent:Ksh.10000</span></h1>
                  <img src="../assets/ten.jpg"  class=" h-80 w-80 rounded-md"  alt="">
                  <a href="about" >   <button class=" ml-20 rounded-md m-5 p-5 bg-green-500  text-white">Accomodate me</button></a>
              </div>
              </div>
              <div class=" flex justify-center mx-auto items-center">
                <div class="">
             <h1> Langat Apartments  <span class=" text-yellow-500"> Rent:Ksh.13000</span></h1>
                  <img src="../assets/five.webp"  class=" h-80 w-80 rounded-md"  alt="">
                  <a href="/about" > <button class=" ml-20 rounded-md m-5 p-5 bg-green-500 text-white">Accomodate me</button></a>
              </div>
              </div>
              <div class="flex justify-center mx-auto items-center ">
                <div class="">
             <h1> kwa ken Apartments  <span class=" text-yellow-500"> Rent:Ksh.4000</span></h1>
                  <img src="../assets/six.jpg"   class=" h-80 w-80 rounded-md" alt="">
                  <a href="/about" >  <button class=" ml-20 rounded-md  m-5 p-5 bg-green-500 text-white ">Accomodate me</button></a>
              </div>
              </div>
    
            <div class=" flex justify-center mx-auto items-center "> 
                <div class="">
             <h1> kwa ken Apartments  <span class=" text-yellow-500"> Rent:Ksh.4000</span></h1>
                 <img src="../assets/lepen.jpg" alt="" class=" h-80 w-80 rounded-md">  
                 <a href="/about" ><button class=" ml-20 rounded-md m-5 p-5 bg-green-500 text-white hover:inset-1">Accomodate me</button></a>
                </div>
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
