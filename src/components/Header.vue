<template>
  <nav class="level">
    <p class="level-item has-text-centered is-size-5">
      <router-link to="/">Home</router-link>
    </p>
    <p class="level-item has-text-centered">
      <a class="link is-info">Menu</a>
    </p>
    <p class="level-item has-text-centered">
      <a class="link is-info">PodPod</a>
    </p>
    <p class="level-item has-text-centered">
      <a class="link is-info">Reservations</a>
    </p>
    <p class="level-item has-text-centered is-size-5">
      <router-link to="/profile">Profile</router-link>
    </p>
    <router-view />
  </nav>
</template>

<script>
export default {
    name: "Header"
};
</script>

<style>
</style>
