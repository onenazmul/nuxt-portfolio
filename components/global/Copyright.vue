<template>
  <div class="copyright text-center">
    <p>
      &copy; {{ new Date().getFullYear() }}, All Rights Reserved by
      <strong>Bijoy Tech</strong>
    </p>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
.copyright {
  margin: 10px 0;
  p {
    margin: 0;
    strong {
      font-weight: 400;
    }
  }
}
</style>
