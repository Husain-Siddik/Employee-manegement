<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import navber from './components/navber.vue';
import navsideitem from './components/navsideitem.vue';
import Footeritem from './components/footeritem.vue';

</script>

<template>
  <header>
    <div class="flex items-center justify-center">
      <div class="flex border md:w-5/6 ">
        <navsideitem />


        <div class=" border w-full h-full">
          <navber />
          <RouterView />
          <Footeritem />
        </div>

      </div>
    </div>
  </header>

 
</template>
