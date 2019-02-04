<template>
  <div class="home">
    <home-top></home-top>
  </div>
</template>

<script>
// @ is an alias to /src
import HomeTop from '@/components/Home/HomeTop.vue';

export default {
  name: 'home',
  components: {
    HomeTop,
  },
};
</script>

<style>
.home {
  position: relative;
  overflow-x: hidden;
}
</style>
