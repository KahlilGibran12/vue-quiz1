<template>
  <nav class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">My Portofolio </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavDropdown">
        <div class="mx-auto"></div>
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="home"><router-link to="/home" style="color: black;">Home</router-link></a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="portofolio"><router-link to="/portofolio" style="color: black;">Portofolio</router-link></a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <router-view />
</template>

<script>

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-image: url(https://img.freepik.com/free-vector/white-abstract-background-design_23-2148825582.jpg?w=1060&t=st=1680104524~exp=1680105124~hmac=3e658578c23f86f4a06488a2b32e720ff67c377ce2b813fc4dc47e18cf436e2b);
  background-size: cover;
}
</style>
