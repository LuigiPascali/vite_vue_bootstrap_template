<script>
  export default {
    data() {
      return {
        title: 'Main Component',
        content: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit.',
      };
    },
  };
</script>
 
<template>

    <main class="main">
      <h2>{{ title }}</h2>
      <p>{{ content }}</p>
    </main>
    
</template>

<style>

  .main {
    padding: 20px;
  }

</style>
  