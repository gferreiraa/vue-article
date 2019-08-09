<template>
  <div class="container">
    <h1>Wubba Lubba Dub-Dub</h1>
    <p>Refresh your page to see <b>new characters!</b></p>
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
h1 {
    background: -webkit-linear-gradient(#FFF720, #3CD500);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    font-family: 'Bigelow Rules', cursive; /* Font link: <link href="https://fonts.googleapis.com/css?family=Bigelow+Rules&display=swap" rel="stylesheet"> */
    font-size: 7em;
    margin-top: 30px;
    margin-bottom: 0px;
}
p {
  color: #CAEE1E;
  margin-bottom: 30px;
}

</style>
