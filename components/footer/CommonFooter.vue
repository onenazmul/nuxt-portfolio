<template>
  <footer class="footer">
    <div class="footer-top">
      <b-container fluid>
        <b-row>
          <b-col md="4 text-center logo-footer">
            <h3><logo></logo></h3>
            <p class="mt-3">
              Making a positive first impression is essential to developing a
              strong customer relationship. Ekko is powerful enough to assist
              any small businesses.
            </p>
            <social></social>
          </b-col>
          <b-col md="4">
            <contact-us></contact-us>
          </b-col>
          <b-col md="2">
            <service-links></service-links>
          </b-col>
          <b-col md="2">
            <quick-links></quick-links>
          </b-col>
        </b-row>
      </b-container>
    </div>
    <div class="footer-bottom">
      <b-row>
        <b-col>
          <copyright></copyright>
        </b-col>
      </b-row>
    </div>
  </footer>
</template>

<script>
import Logo from '@/components/global/Logo'
import Social from '@/components/global/Social'
import ContactUs from '@/components/global/ContactUs'
import QuickLinks from '@/components/global/QuickLinks'
import ServiceLinks from '@/components/global/ServiceLinks'
import Copyright from '@/components/global/Copyright'
export default {
  components: {
    Logo,
    Social,
    Copyright,
    ServiceLinks,
    QuickLinks,
    ContactUs
  }
}
</script>
