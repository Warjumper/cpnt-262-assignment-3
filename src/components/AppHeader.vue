<template>
  <div class="header">
    <button>{{ btnText }}</button>
  </div>
</template>

<script>
 export default {
  props: ['btnText']
 };
  
</script>

<style>
body {
  padding: 0;
  margin: 0;
}

button {
  display: block;
  margin: auto;
  background-color: #111;
  font-size: 60px;
  border-radius: 20px;
  padding: 10px;
  color: white; 
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}

.header {
  background-image: url("https://cdnb.artstation.com/p/assets/images/images/030/581/089/large/edwin-sablaya-azathot2e.jpg?1601028438");
  background-position: center;
  background-repeat: no-repeat;
  position: relative;
  background-size: cover;
  display: block;
  min-height: 250px;
  padding-top: 160px;
  padding-bottom: 0;
}
</style>