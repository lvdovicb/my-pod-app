<template>
  <section>
    <Header></Header>
    <article class="message is-info container">
      <div class="message-header">
        Info
        <button class="delete"></button>
      </div>
      <div class="content message-body">
          <h1>
          This is the profile page.
          </h1>
          <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Rem, incidunt? Adipisci est laudantium, libero impedit minus modi iusto at magnam suscipit expedita. Illo quisquam necessitatibus nesciunt voluptatem voluptatum saepe mollitia.
          </p>
      </div>
    </article>
  </section>
</template>

<script>
import Header from "../components/Header";
export default {
  name: "Profile",
  components: {
    Header
  }
};
</script>
<style>
</style>
