<script setup lang="ts">
</script>
<template>
  <div>
    <nav>
      <NuxtLink to="/">index</NuxtLink>
      <NuxtLink to="/sub/123">sub 123</NuxtLink>
    </nav>
    
    <NuxtPage></NuxtPage>
<!--    <RouterView v-slot="{ Component, route }">
      <KeepAlive :max="2">
        <Component :is="Component" :key="route.path"/>
      </KeepAlive>
    </RouterView>-->
  </div>
</template>

<style>
nav {
  display: flex;
  gap: 1rem;
}
</style>