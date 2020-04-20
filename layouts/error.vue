<template>
  <div class="error-content">
    <div class="container-fluid text-center">
      <b-row>
        <b-col>
          <b-img src="~/assets/img/error.gif" center></b-img>
          <h1 v-if="error.statusCode === 404">Page not found</h1>
          <h1 v-else>An error occurred</h1>
          <p>We are sorry, the page you are looking is not found.</p>
          <nuxt-link to="/" class="btn btn-primary">Back to Homepage</nuxt-link>
        </b-col>
      </b-row>
    </div>
  </div>
</template>

<script>
export default {
  /* eslint-disable */
  props: ['error'],
  head() {
    title: '404 - Bijoy Tech'
  }
}
</script>
<style scoped>
.error-content {
  padding: 6rem 0;
}
img {
  margin-bottom: 30px;
}
a {
  margin-top: 25px;
}
</style>
