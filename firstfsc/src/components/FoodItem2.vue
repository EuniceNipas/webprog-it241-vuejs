<template>
  <divclass="berries">
    <h2>{{ name }}</h2>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: 'Little Lad',
      message: 'Im a little lad who loves berries and cream 🕺  I hope u get my reference 🙏'
    }
  }
};
</script>

<style>

  .berries {
    border: dashed black 1px;
    display: inline-block;
    margin: 10px;
    padding: 10px;
    background-color: blue;
  }
  
  </style>