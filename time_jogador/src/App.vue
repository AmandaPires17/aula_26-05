<script setup>
import { RouterLink, RouterView} from "vue-router";
import HomeRouter from "@/components/HomeRouter.vue";
</script>

<template>
<header>

<div class="ola">
  <HomeRouter msg="Olá Mundo!!!" />
  
  <nav>
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/times">Times</RouterLink>
    <RouterLink to="/jogadores">Jogadores</RouterLink>
  </nav>
  </div>

  </header>

   <RouterView />
</template>