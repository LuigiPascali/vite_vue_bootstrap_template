<script>

  export default {
    data() {
      return {
        title: 'Header Component',
      };
    },
  };

</script>

<template>

    <header class="header">
      <h1>{{ title }}</h1>
    </header>
    
</template>
  
<style>

  .header {
    background-color: #f8f9fa;
    padding: 20px;
  }

</style>
  