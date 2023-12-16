<template>
    <div>
      <h1>Bibliography View</h1>
      <div class="video-container">
        <!-- Código para el reproductor de YouTube -->
        <iframe width="320" height="180" src="https://www.youtube.com/embed/8usSAMpuSVI" frameborder="0" allowfullscreen></iframe>
      </div>
      <!-- Enlaces clicables -->
      <ul>
        <li><a href="https://www.worldhistory.org/article/1504/the-wars-of-the-roses-consequences--effects/" target="_blank">Wars of the Roses - World History</a></li>
        <li><a href="https://en.wikipedia.org/wiki/Wars_of_the_Roses" target="_blank">Wars of the Roses - Wikipedia</a></li>
        <li><a href="https://www.britannica.com/event/Wars-of-the-Roses" target="_blank">Wars of the Roses - Britannica</a></li>
        <li><a href="https://schoolshistory.org.uk/topics/british-history/wars-of-the-roses/causes-of-the-wars-of-the-roses/" target="_blank">Causes of the Wars of the Roses - Schoolshistory.org.uk</a></li>
      </ul>
    </div>
  </template>
  
  <script>
  export default {
    name: 'BibliographyView',
    // ...
  };
  </script>
  
  <style>
  /* Estilos para la vista de Bibliography */
  /* ... tus estilos ... */
  
  /* Estilos para el contenedor del video */
  .video-container {
    display: flex;
    justify-content: center;
    margin-top: 20px; /* Espacio opcional arriba del video */
  }
  
  .video-container iframe {
    width: 1000px; /* Ancho del video */
    height: 540px; /* Altura del video */
  }
  </style>
  