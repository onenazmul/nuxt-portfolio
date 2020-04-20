<template>
  <!-- Right aligned nav items -->
  <b-navbar-nav class="ml-auto">
    <li>
      <nuxt-link to="/about" class="nav-link">About us</nuxt-link>
    </li>
    <li>
      <nuxt-link to="/courses" class="nav-link">Courses</nuxt-link>
      <ul class="dropdown">
        <li>
          <nuxt-link :to="{ name: 'courses' }">Course</nuxt-link>
        </li>
        <li>
          <nuxt-link :to="{ name: 'courses' }">Course</nuxt-link>
        </li>
        <li>
          <nuxt-link :to="{ name: 'courses' }">Course</nuxt-link>
        </li>
      </ul>
    </li>
    <li>
      <nuxt-link to="/services" class="nav-link">Services</nuxt-link>
    </li>
    <li>
      <nuxt-link to="/services" class="nav-link">Other</nuxt-link>
    </li>
    <a href="/contact" class="nav-link">Contact</a>
  </b-navbar-nav>
</template>

<script>
export default {}
</script>

<style></style>
