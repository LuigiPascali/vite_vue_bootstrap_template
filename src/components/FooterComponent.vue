<script>
  export default {
    data() {
      return {
        text: 'Footer Component',
      };
    },
  };
</script>

<template>

    <footer class="footer">
      <p>{{ text }}</p>
    </footer>
    
</template>
  
<style>

  .footer {
    background-color: #f8f9fa;
    padding: 20px;
  }

</style>
  