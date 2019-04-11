<template>
  <section>
    <Header></Header>
    <div class="home container">
      <b-field label="Search">
        <b-input icon-pack="fas" icon="search" type="search" class="level-item"></b-input>
      </b-field>
      <HelloWorld msg="Welcome to Your Vue.js App"/>
    </div>
  </section>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import Header from "@/components/Header.vue";

export default {
  name: "home",
  components: {
    HelloWorld,
    Header
  }
};
</script>
