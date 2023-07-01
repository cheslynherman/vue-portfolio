<template>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <router-link class="navbar-brand" to="/"><img src="https://i.postimg.cc/HLY5w0rN/Frame-1.png" alt="Logo" class="navImage"></router-link>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
      <div class="navbar-nav">
        <router-link to="/" class="navButtons">Home</router-link>
        <router-link to="" class="navButtons">Projects & Testimonials</router-link>
        <router-link to="" class="navButtons">About</router-link>
        <router-link to="" class="navButtons">Resume</router-link>
        <router-link to="" class="navButtons">Contact</router-link>
      </div>
    </div>
  </div>
</nav>
</template>

<style scoped>
    nav {
        background-color: #3C2A21 !important;
    }
    .navImage {
        height: 60px;
        width: 60px;
    }
    .navbar-nav {
        margin-left: auto;
    }
    .navButtons {
        margin-left: 20px;
        color: #3C2A21;
        border: 2px solid #EDE4E0;
        background: #EDE4E0;
        padding: 10px;
        border-radius: 15px;
    }
    a {
        text-decoration: none;
    }
</style>