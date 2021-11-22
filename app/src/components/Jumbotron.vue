<template>
  <div class="jumbo">
      <img src="../assets/wallpaper.jpg" alt="">
  </div>
</template>

<script>
export default {
    name: 'Jumbo'
}
</script>

<style scoped>
.jumbo {
    height: 600px;
    width: 100%;
    background-color: red
}

.jumbo img {
    height: 100%;
    width: 100%;
    object-fit: cover;
}
</style>