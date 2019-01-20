<template>
  <div id="app">
    <nav class="bg-white h-12 shadow mb-8 px-6 md:px-0">
      <div class="container mx-auto h-full">
        <div class="flex items-center justify-center h-12">
          <router-link to="/" class="no-underline mr-4">Home</router-link>
          <router-link to="/about" class="no-underline">About</router-link>
        </div>
      </div>
    </nav>


    <router-view/>
  </div>
</template>

<style src="./styles/main.css"></style>
