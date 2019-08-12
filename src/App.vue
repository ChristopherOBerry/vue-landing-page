<template>
  <div id="app">
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary border-bottom">
      <router-link class="navbar-brand" to="home">Christopher O'Berry</router-link>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarColor01"
        aria-controls="navbarColor01"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarColor01">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item">
            <router-link class="nav-link" to="home">About me</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" to="tools">Tools</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" to="projects">My Projects</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" to="about">Contact</router-link>
          </li>
        </ul>
      </div>
    </nav>
    <router-view class="container-fluid"></router-view>
  </div>
</template>

<script>
export default {
  name: "App"
};
</script>

<style>
h1,
h2,
h3,
h4,
h5,
h6 {
  color: white;
}
</style>
