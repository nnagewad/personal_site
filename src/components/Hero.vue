<template>
  <section class="hero is-medium" id="hero">
    <div class="hero-body">
      <div class="container">
        <div class="columns is-multiline">
          <div class="column is-narrow bottom-paddingless">
            <h1 class="title is-lowercase is-1">Nikin Nagewadia</h1>
          </div>
          <div class="column is-two-thirds">
            <p class="subtitle">Interaction designer</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Hero"
};
</script>

<style lang="scss" scoped>
  @import '../assets/sass/mystyles.scss';

  .hero {
    background-color: $site-green;
  }

  .title, .subtitle {
    color: $site-white;
  }

  .bottom-paddingless {
    padding-bottom: 0;
  }
</style>
