<template>
  <div class="contact-box-wrapper">
    <div class="contact-box">
      <div class="icon">
        <img src="@/assets/img/mail.png" alt="Location" />
      </div>
      <div class="contact-details">
        <h5>Contact Us</h5>
        <p>
          <a href="tel:+8801688138948">+880 1688 138948</a><br />
          <a href="mailto:info@bijoytech.com">info@bijoytech.com</a>
        </p>
      </div>
    </div>
    <span class="separator"></span>
    <div class="contact-box">
      <div class="icon">
        <img src="@/assets/img/location.png" alt="Location" />
      </div>
      <div class="contact-details">
        <h5>Bangladesh Office</h5>
        <p>56/2, Dynasty Waheed Tower, West PanthaPath, Dhanmondi</p>
      </div>
    </div>
    <span class="separator"></span>
    <div class="contact-box">
      <div class="icon">
        <img src="@/assets/img/location.png" alt="Location" />
      </div>
      <div class="contact-details">
        <h5>USA Office</h5>
        <p>56/2, Dynasty Waheed Tower, West PanthaPath, Dhanmondi</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
.contact-box-wrapper {
  .contact-box {
    display: flex;
    .icon {
      img {
        max-width: 50px;
      }
      margin-top: 12px;
      margin-right: 9px;
    }
  }
  span.separator {
    width: 80%;
    height: 1px;
    background: #fff8f533;
    display: block;
    margin-bottom: 14px;
  }
}
@media only screen and (max-width: 767px) {
  footer {
    .contact-box-wrapper {
      margin: 40px 0 30px;
    }
  }
}
</style>
