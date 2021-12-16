<template>
  <footer  class="footer">
    <div class="container">
      <div class="row">
        <div class="col-12 col-lg-6">
          <Logo />
        </div>
        <div class="col-12 mt-5">
          <div class="row">
            <div class="col-12 col-lg-3">
              <figure class="footer__location">
                <img src="@/assets/images/icon-location.svg" alt="icon location" class="footer__location-icon" />
              </figure>
              <p class="footer__location-description">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
              </p>
            </div>
            <div class="col-12 col-lg-3">
              <div class="d-flex align-items-center">
                <figure class="footer__location">
                  <img src="@/assets/images/icon-phone.svg" alt="icon location" class="footer__location-icon" />
              </figure>
                <address>+1-543-123-4567</address>
              </div>
              <div class="d-flex align-items-center">
                <figure class="footer__location">
                  <img src="@/assets/images/icon-email.svg" alt="icon location" class="footer__location-icon" />
                </figure>
                <address>example@fylo.com</address>
              </div>
            </div>
            <div class="col-12 col-lg-3">
              <div class="row flex-nowrap">
                <div class="col-12 col-md-6">
                  <ul class="m-0 p-0">
                    <li class="pb-2"><a href="#About" class="footer__link">About Us</a></li>
                    <li class="pb-2"><a href="#Jobs" class="footer__link">Jobs</a></li>
                    <li class="pb-2"><a href="#Press" class="footer__link">Press</a></li>
                    <li class="pb-2"><a href="#Blog" class="footer__link">Blog</a></li>
                  </ul>
                </div>
                <div class="col-12 col-md-6">
                  <ul class="m-0 p-0">
                    <li class="pb-2"><a href="#Contact" class="footer__link">Contact Us</a></li>
                    <li class="pb-2"><a href="#Terms" class="footer__link">Terms</a></li>
                    <li class="pb-2"><a href="#Privacy" class="footer__link">Privacy</a></li>
                  </ul>
                </div>
              </div>
            </div>
            <div class="col-12 col-lg-3">
              <div class="d-flex align-items-center">
                <div class="footer__social-network">
                  <span></span>
                </div>
                <div class="footer__social-network">
                  <span></span>
                </div>
                <div class="footer__social-network">
                  <span></span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
  export default {
    name: 'Footer',
  }
</script>

<style lang="scss" scoped>
  .footer {
      margin-top: 100px;
      background-color: $DarkBlueFooter;
  }
</style>