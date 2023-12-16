<template>
  <nav class="navbar">
    <ul class="nav-links">
      <li><router-link to="/">Home</router-link></li>
      <li><router-link to="/abstract">Abstract</router-link></li>
      <li><router-link to="/Essay">Essay</router-link></li>
      <li><router-link to="/bibliography">Bibliography</router-link></li>
      <li><router-link to="/Credits">Credits</router-link></li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: 'NavbarRoses',
};
</script>

<style>
/* Estilos para el menú de navegación */
.navbar {
  background-color: #333; /* Color de fondo del navbar */
  padding: 10px; /* Espaciado interno */
  /* Otros estilos según sea necesario */
}

.nav-links {
  list-style-type: none; /* Elimina viñetas de la lista */
  display: flex; /* Mostrar en línea horizontal */
  justify-content: center; /* Centrar los enlaces */
}

.nav-links li {
  margin: 0 10px; /* Espacio entre elementos de la lista */
}

.nav-links a {
  color: white; /* Color del texto de los enlaces */
  text-decoration: none; /* Elimina subrayado */
  font-weight: bold; /* Texto en negrita */
  /* Otros estilos de enlaces */
}

.nav-links a:hover {
  color: #ffd700; /* Cambia el color al pasar el cursor */
  /* Otros estilos hover */
}
</style>

  