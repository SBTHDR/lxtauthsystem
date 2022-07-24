<template>
  <div>
      <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
            <div class="container">
                <a class="navbar-brand" href="#">LxtauthSystem</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                    <div class="navbar-nav">
                        <nuxt-link class="nav-link active" aria-current="page" :to="{ name: 'index' }">Home</nuxt-link>                
                        <nuxt-link class="nav-link" :to="{ name: 'login' }">Login</nuxt-link>
                        <a class="nav-link" href="#">About</a>
                    </div>
                </div>
            </div>
        </nav>

        <div class="container mt-3">
            <Nuxt />
        </div>
  </div>
</template>

<style>
    @import url('https://cdn.jsdelivr.net/npm/bootstrap@5.1.1/dist/css/bootstrap.min.css');
</style>