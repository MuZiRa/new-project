<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="bg-blue-100" ><br><br>
<h1 class="text-2xl font-extrabold text-gray-900">My Personal Details</h1><br>   
    <img class="inline-block h-12 w-13 rounded-full ring-2 ring-white" src="./assets/photo.jpg"><br><br>   
  </div>

  <div class="bg-white shadow overflow-hidden sm:rounded-lg">
    <div class="border-t border-grey-200">
      <dl>
        <div class="bg-green-200 px-4 py-5 sm:grid sm:grid-cols-3 sm:gap-4 sm:px-6">
          <dt class="text-sm font-medium text-gray-500">Fullname</dt>
          <dd class="mt-1 text-sm text-gray-900 sm:mt-0 sm:col-span-2">Nur Rahmah Binti Brahim</dd>
        </div>
        <div class="bg-blue-50 px-4 py-5 sm:grid sm:grid-cols-3 sm:gap-4 sm:px-6">
          <dt class="text-sm font-medium text-gray-500">Student ID</dt>
          <dd class="mt-1 text-sm text-gray-900 sm:mt-0 sm:col-span-2">20FTT1818</dd>
        </div>
        <div class="bg-green-200 px-4 py-5 sm:grid sm:grid-cols-3 sm:gap-4 sm:px-6">
          <dt class="text-sm font-medium text-gray-500">Student Email</dt>
          <dd class="mt-1 text-sm text-gray-900 sm:mt-0 sm:col-span-2">20FTT1818@student.pb.edu.bn</dd>
        </div>
        <div class="bg-blue-50 px-4 py-5 sm:grid sm:grid-cols-3 sm:gap-4 sm:px-6">
          <dt class="text-sm font-medium text-gray-500">Course</dt>
          <dd class="mt-1 text-sm text-gray-900 sm:mt-0 sm:col-span-2">Level 5 Diploma In Web Development</dd>
        </div>

      </dl>
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
