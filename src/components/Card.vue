<template>
  <div class="card-container">
    <img
      :src="characterList.image"
      alt="avatar-image"
    >
    <p>Name: {{ characterList.name }}</p>
    <p>Status: {{ characterList.status }}</p>
    <p>Species: {{ characterList.species }}</p>
  </div>
</template>

<script>

export default {
    name: "Card",
    props: ['characterList']
}
</script>

<style>
.card-container {
  display: flex;
  flex-direction: column;
  background-color: #ffffff;
  border: 1px solid grey;
  border-radius: 5px;
  padding: 25px;
  cursor: pointer;
  -moz-osx-font-smoothing: grayscale;
  backface-visibility: hidden;
  transform: translateZ(0);
  transition: transform 0.25s ease-out;
}

/* .card-container:hover {
  transform: scale(1.05);
} */
</style>
