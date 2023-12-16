<template>
    <div class="credits">
      <h1 class="credits-title">Credits</h1>
      <ul class="credits-list">
        <br>
        <li class="credit-name">Irene González - 1667224</li>
        <li class="credit-name">Judith Bonilla</li>
        <li class="credit-name">Núria Plà</li>
        <li class="credit-name">Adrià Bagué</li>
      </ul>
    </div>
  </template>
  
  <script>
  export default {
    name: 'CreditsView',
  };
  </script>
  
  <style>
  .credits {
    text-align: center;
    margin-top: 10px;
    padding: 5vw;
    height: 100vh;
    background-image: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('../assets/rooses.jpg');
    background-size: cover;
    background-position: center;
  }
  
  .credits-title {
    font-size: 3.5vw; /* Tamaño de fuente más pequeño */
    color: #fff;
    margin-bottom: 3vw; /* Margen inferior reducido */
  }
  
  .credits-list {
    list-style: none;
    padding: 0;
    margin-top: 3vw; /* Margen superior reducido */
  }
  
  .credit-name {
    font-size: 2.5vw; /* Tamaño de fuente más pequeño */
    margin-bottom: 2vw; /* Margen inferior reducido */
    color: #fff;
  }
  </style>
  
  
  
  
  
  