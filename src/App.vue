<template>
  <HomeView />
</template>

<script>
import HomeViewvue from './views/HomeView.vue'
import HomeView from './views/HomeView.vue'

export default {
    name: "App",
    views: {
        HomeViewvue
    },
    components: { HomeView }
}
</script>

<style>
@import '@/assets/base.css';
</style>
