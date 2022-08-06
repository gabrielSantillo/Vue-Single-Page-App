<template>
  <div>
    <img alt="" src="https://www.reshot.com/preview-assets/icons/Y63ZACEGFT/diamond-Y63ZACEGFT.svg">
    
    <a href="#">Home</a>
    <a href="#">About us</a>
    <a href="#">Contact</a>
  </div>
</template>

<script>
  export default {
    
  }
</script>

<style scoped>

div {
display: grid;
grid-template-columns: 5fr 1fr 1fr 1fr;
place-items: center;
}
img {
  width: 50px;
  justify-self: start;
  margin-left: 20px;
}

a {
  text-decoration: none;
  color: black;
}

a:hover {
  color: cornflowerblue;
}
</style>
