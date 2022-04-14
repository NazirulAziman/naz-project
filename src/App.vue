<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="bg-blue-100 grid place-items-center min-h-screen">
    <div class="p-4 w-8/12 grid gap-4 sm:grid-cols-2 xl:grid-cols-3">
      <img src="./assets/myPic.jpeg" class="w-30 m-auto">

      <div class="h-full w-full bg-violet-200 p-5">
        <h1 class="font-bold text-2xl text-violet-700 underline pb-4">NazirulAziman Bin Abu Bakar</h1>
        <ul class="text-lg bold">
		      <li>Student ID : 20FTT1440</li>
          <li>Group Code : DWDT06</li>
	      </ul>
        <h1 class="text-xl font-bold mt-5">About Me!</h1>
        <p>My Name is NazirulAziman and my colleague usually called me Naz, 
          I am an introvert and like to learn more on programming languages also interested on making a web design.
        </p>
      </div>

      <div class="h-full w-full bg-slate-300 p-5">
      <h1 class="text-2xl text-pink-500 font-bold underline">Hobbies</h1>
        <ul class="text-lg bold">
		      <li>PLaying Video Games</li>
          <li>Watching Anime</li>
          <li>Reading Manhwa</li>
	      </ul>
        <img src="./assets/4.png" class="w-6/12 m-auto pt-5">
      </div>

      <div class="h-full w-full bg-violet-200 p-4">
        <h1 class="text-2xl text-red-800 font-bold underline">Interest</h1>
        <ul class="text-lg bold">
		      <li>Playing Music</li>
          <li>Drawing</li>
          <li>Martial Arts</li>
	      </ul>
        <img src="./assets/1.png" class="w-6/12 m-auto pt-5">
      </div>

      <div class="h-full w-full bg-slate-300 p-4">
        <h1 class="text-2xl text-green-600 font-bold underline">Education</h1>
        <ul class="text-lg bold">
		      <li>'O' Level</li>
          <li>HNTec in Information Technology</li>
          <li>Diploma in Web Development</li>
	      </ul>
        <img src="./assets/3.png" class="w-6/12 m-auto pt-5">
      </div>

      <div class="h-full w-full bg-violet-200 p-4">
        <h1 class="text-2xl text-blue-500 font-bold underline">Experience</h1>
        <ul class="text-lg bold">
		      <li>IT Network Assitant</li>
          <li>Nurse Call Technician</li>
          <li>Web Developer</li>
	      </ul>
        <img src="./assets/2.png" class="w-6/12 m-auto pt-5">
      </div>

    </div>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
