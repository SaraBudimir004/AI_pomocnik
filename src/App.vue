<template>
  <div id="app">
    <NavigationBar />
    <SignUp/>
  </div>
</template>

<script>
import NavigationBar from './components/NavigationBar.vue';
import SignUp from './components/SignUp.vue';

export default {
  name: 'App',
  components: {
    NavigationBar,
    SignUp
  },
};
</script>

<style scoped>

</style>
