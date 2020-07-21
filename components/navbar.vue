<template>
  <b-navbar toggleable="lg">
    <b-navbar-brand href="#">
      Logo
    </b-navbar-brand>
    <b-navbar-toggle target="nav-collapse" />
    <b-collapse id="nav-collapse" is-nav>
      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
        <b-nav-item href="#">
          <nuxt-link to="/quienes-somos">
            ¿Quienes somos?
          </nuxt-link>
        </b-nav-item>
        <b-nav-item href="#">
          <nuxt-link to="/quienes-somos">
            ¿Quienes somos?
          </nuxt-link>
        </b-nav-item>
        <b-nav-item href="#">
          <nuxt-link to="/contacto">
            Contacto
          </nuxt-link>
        </b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script>
</script>

<style>
</style>
