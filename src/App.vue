<script setup>
import { RouterView } from 'vue-router'
import NavBar from './components/NavBar.vue';
import FooterComp from './components/FooterComp.vue'
</script>

<template>
 <NavBar/>
<RouterView />
  <FooterComp/>

</template>
