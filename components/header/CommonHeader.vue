<template>
  <header class="header">
    <div class="top-part">
      <b-container fluid>
        <b-row>
          <b-col sm="6">
            <social></social>
          </b-col>
          <b-col sm="6" class="text-right">
            <a href="tel:+8801711234567"
              ><i class="fas fa-phone-alt"></i> +880 1711 234 567</a
            >
            &nbsp; &nbsp;
            <a href="mailto:info@bijoytech.com"
              ><i class="fas fa-envelope"></i> info@bijoytech.com</a
            >
          </b-col>
        </b-row>
      </b-container>
    </div>
    <b-container fluid>
      <b-navbar toggleable="lg">
        <b-navbar-brand>
          <logo></logo>
        </b-navbar-brand>
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
        <b-collapse id="nav-collapse" is-nav>
          <main-menu></main-menu>
        </b-collapse>
      </b-navbar>
    </b-container>
  </header>
</template>

<script>
import Logo from '@/components/global/Logo'
import Social from '@/components/global/Social'
import MainMenu from '@/components/header/MainMenu'
export default {
  components: { Logo, MainMenu, Social }
}
</script>

<style></style>
