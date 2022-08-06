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
* {
    margin: 0;
    padding: 0;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    width: 100%;
    
}

div {
display: grid;
grid-template-columns: 5fr 1fr 1fr 1fr;
place-items: center;
transform: translateY(-50px);
}
img {
  width: 50px;
  justify-self: start;
  margin-left: 20px;
}

a {
  text-decoration: none;
  color: black;
  text-align: center;
}

a:hover {
  color: cornflowerblue;
}
</style>
