<template>
  <HomeView />
</template>

<script>
import HomeView from './views/Home/HomeView.vue'

export default {
    name: "App",
    views: { HomeView },
    components: { HomeView }
}
</script>

<style>
@import '@/assets/base.css';
</style>
