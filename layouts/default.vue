<template>
  <div class="wrapper">
    <common-header></common-header>
    <nuxt />
    <common-footer></common-footer>
  </div>
</template>
<script>
import CommonHeader from '@/components/header/CommonHeader'
import CommonFooter from '@/components/footer/CommonFooter'
export default {
  components: { CommonHeader, CommonFooter }
}
</script>
