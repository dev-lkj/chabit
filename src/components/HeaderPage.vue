<template>
    <header class="header">
        <h1 class="home">Chabit</h1>
    </header>
  </template>
  
  <script>
  export default {
    name: 'HeaderPage',
    props: {
    //   msg: String
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
    .header{
        position:sticky;
        left:0;
        top:0;
        z-index: 10;
        width:100%;
        height:80px;
        background-color: rgba(255,255,255,0.1);
        display:flex;
        align-items: center;
    }
    .home{
        margin-left:100px;
        color:#fff;
        font-size:18px;
        font-weight: 700;
    }
  </style>
  