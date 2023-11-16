<template>
          <h1>UserCard</h1>
  <UserCard
      username="Pedro Hernández"
      email="pedrohernandez@gmail.com"
      biography="Soy un apasionado desarrollador de software con más de 5 años de experiencia en el campo. Me especializo en el desarrollo web y móvil, utilizando tecnologías como Vue.js, React y Node.js. Mi enfoque principal es crear aplicaciones elegantes, eficientes y fáciles de usar. En mi tiempo libre, disfruto explorando nuevas tecnologías, contribuyendo a proyectos de código abierto y participando en hackathons. ¡Siempre estoy emocionado por aprender y enfrentar nuevos desafíos en el mundo del desarrollo de software!"

  />
</template>

<script>
import UserCard from "./components/UserCard.vue";

export default {
  name: 'App',
  components: {
    UserCard
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 0% 10%;
  margin-top: 60px;
  }

</style>
