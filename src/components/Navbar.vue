<template>
  <div class="pb-5">
    <b-navbar toggleable="lg" type="dark" variant="info">
      <b-navbar-brand href="#">Rick and Morty</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item :to="'home'">INICIO</b-nav-item>
          <b-nav-item href="#">BUSCAR</b-nav-item>
          <b-nav-item href="#">ACERCA DE </b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
