<template>
  <div class="inner-content">
    <b-container>
      <b-row>
        <b-col class="text-center mb-4">
          <h1>Let's get connected</h1>
          <p>
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quod
            voluptatem incidunt eos repellat hic quas dolores tenetur expedita
            ratione neque.
          </p>
        </b-col>
      </b-row>
      <b-row>
        <b-col md="6">
          <script>
            hbspt.forms.create({
              portalId: '6078155',
              formId: 'd6cddb00-1e98-4bfa-88d9-fd5c3d0b1d5f'
            })
          </script>
        </b-col>
        <b-col md="6">
          <iframe
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3651.854773148267!2d90.37867221486079!3d23.752557684588286!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3755b9f7e9a6c3b3%3A0x61956801bb9b9e4a!2sDynasty%20Wahed%20Tower!5e0!3m2!1sen!2sbd!4v1584902777028!5m2!1sen!2sbd"
            width="100%"
            height="450"
            frameborder="0"
            style="border:0;"
            allowfullscreen
            aria-hidden="false"
            tabindex="0"
          ></iframe>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: 'Contact Us',
      script: [{ src: 'https://js.hsforms.net/forms/shell.js' }]
    }
  }
}
</script>

<style scoped>
@media only screen and (max-width: 767px) {
  form {
    margin-bottom: 50px;
  }
}
</style>
