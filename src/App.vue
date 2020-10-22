<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/riddles">Riddles</router-link> |
    <router-link to="/about">About</router-link>
  </div>
  <router-view />
</template>

<script>
export default {
  components: {},
};
</script>

<style lang="scss"></style>
