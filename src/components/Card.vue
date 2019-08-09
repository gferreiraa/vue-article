<template>
  <div class="card-container">
    <img
      :src="characterList.image"
      alt="avatar-image"
    >
    <p><span>Name:</span> {{ characterList.name }}</p>
    <p class="medium__item"><span>Status:</span> {{ characterList.status }}</p>
    <p class="last__item"><span>Species:</span> {{ characterList.species }}</p>
  </div>
</template>

<script>

export default {
    name: "Card",
    props: ['characterList']
}
</script>

<style scoped>
.card-container {
  display: flex;
  flex-direction: column;
  background-color: #ffffff;
  border-radius: 20px;
  /*padding: 25px;*/
  cursor: pointer;
  -moz-osx-font-smoothing: grayscale;
  backface-visibility: hidden;
  transform: translateZ(0);
  transition: transform 0.25s ease-out;
}

img {
  border-top-left-radius: 20px;
  border-top-right-radius: 20px;
}

.medium__item{
    margin-top: 5px;
}

.last__item{
  margin-bottom: 20px;
  margin-top: 5px;
}

span {
  font-weight: bold;
  font-size: 14px;  
}

/* .card-container:hover {
  transform: scale(1.05);
} */
</style>
