<template>
  <div id="navbar">
    <nav class="navbar navbar-expand-lg fixed-top bg-body-tertiary" style="background-color: #23293F;">
      <div class="container">
        <img src="https://i.pinimg.com/originals/b0/c2/54/b0c2542fe6ac0194cb845d3a155e6957.png"
             alt="Hai" width="45" height="40" class="rounded-circle">
        <div id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <router-link to="/" style="color: white">Home</router-link>
              |
            </li>
            <li class="nav-item">
              |
              <router-link to="/AboutMe" style="color: white">About</router-link>
              |
            </li>
            <li class="nav-item">
              |
              <router-link to="/MyContact" style="color: white">Contact</router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </div>
    <p class="modal-footer; fixed-bottom" style="color: white; background-color: #23293F">Copyright by Syakira</p>
  <router-view></router-view>
</template>

<script>
export default {
  name: 'App',
  components: {}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin-top: 50px;
  text-align: center;
  background-color: #D8D6D5;
  padding-bottom: 0;
}

#navbar {
  color: white;
  padding-bottom: 0;
  margin-bottom: 0;
}

li {
  text-decoration: none;
}

body{
  background-color: #4A4C57;
}

p{
  padding: 10px;
  color: white;
}
</style>
