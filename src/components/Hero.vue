<template>
  <div class="hero">

    <h3>Questo invece è un JUMBOTRON qualsiasi</h3>

    
  </div>
</template>

<script>
export default {
  name: 'Hero'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
    font-size: 20px;
    color: darkgreen;
    border: 2px solid grey;
    border-radius: 10px;
    padding: 15px;
    background-color: rgb(212, 212, 212);
    margin: 100px;
}
.hero {
    height: 60%;
    background-image: url("https://i.ytimg.com/vi/taLKQfoS87I/maxresdefault.jpg");
    background-position: 50% 44%;
    background-size: cover;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 10px;

}

</style>