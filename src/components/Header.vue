<template>
  <div class="container">
    <h1>Wubba Lubba Dub-Dub</h1>
    <p>Refresh your page to see new characters!</p>
  </div>
</template>

<script>
    export default {
        name: "Header"
    }
</script>

<style scoped>
.container {
    display: flex;
    flex-direction: column;
    align-items: center;
}
p {
  color: #CAEE1E;
  margin-bottom: 30px;
}

</style>
