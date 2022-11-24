<template>
  <div class="nav">
  <!-- <img src="src/assets/logo.svg" height=20px width="20px" alt=""> -->

    <ul>
      <li><a href="#">HOME</a></li>
      <li><a href="#">ABOUT</a></li>
      <li><a href="#">STORIES</a></li>
      <li><a href="#">BIO</a></li>
    </ul>

  </div>
</template>

<style scoped>
  .nav { 
    height: 60px; 
    background-color: #333;
  }
  .nav ul {
    list-style: none;
    margin: 0px;
    padding: 10px;
  }
  .nav ul li {
    display: block;
    float: left;
  }
  .nav ul li a {
    text-decoration: none;
    display: block;
    padding: 14px;
    color: white;
  }
</style>