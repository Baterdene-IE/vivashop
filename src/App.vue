<template>
  <div class="container">
    <div class="row mb-2 mt-5">
      <div class="col-md-3"></div>
      <div class="col-md-6">
        <input class="form-control me-2" type="search" placeholder="Хайх" aria-label="Search">
      </div>
      <div class="col-md-3"></div>
    </div>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <a class="navbar-brand" href="#">vi</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <router-link to="/">
            <li class="nav-item">
              <a class="nav-link" href="#">Home</a>
            </li>
          </router-link>
          <router-link to="/about">
            <li class="nav-item">
              <a class="nav-link" href="#">About</a>
            </li>
          </router-link>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact</a>
          </li>
        </ul>
      </div>
    </nav>
  </div>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
