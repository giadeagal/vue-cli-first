<template>
  <div class="hello">
    <div class="shade">
        <img src="../assets/poke-jumbo.jpg" alt="">
        <h2>Benvenuti!</h2>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Hero',
}
</script>

<style scoped>
img {
    max-width:100%;
}

.shade {
    width: 50%;
    margin: auto;
    position: relative;
}

h2 {
    position: absolute;
    top:0;
    left: 50%;
    transform: translateX(-50%);
    color:#41b883;
    font-size: 2rem;
    text-shadow: 1px 2px #000;
}
</style>