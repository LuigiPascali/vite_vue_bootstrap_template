<script>
  import HeaderComponent from './components/HeaderComponent.vue';
  import MainComponent from './components/MainComponent.vue';
  import FooterComponent from './components/FooterComponent.vue';

  import '../src/styles.scss';

  export default {
    components: {
      HeaderComponent,
      MainComponent,
      FooterComponent,
    },
  };
</script>

<template>

  <div id="app">
    <HeaderComponent />
    <MainComponent />
    <FooterComponent />
  </div>

</template>

<style>
  #app {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
  }
</style>
