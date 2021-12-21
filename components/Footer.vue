<template>
  <footer  class="footer">
    <div class="container">
      <div class="row">
        <div class="col-12 col-lg-6">
          <Logo />
        </div>
        <div class="col-12 mt-5">
          <div class="row justify-content-between">
            <div class="col-12 col-lg-4 d-flex">
              <figure class="m-0 mr-4">
                <img src="@/assets/images/icon-location.svg" alt="icon location" class="footer__location-icon" />
              </figure>
              <p class="text footer__location-description">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
              </p>
            </div>
            <div class="col-12 col-lg-3 ">
              <address>
                <div class="d-flex align-items-center mb-4">
                  <figure class="m-0 mr-4">
                    <img src="@/assets/images/icon-phone.svg" alt="icon location" class="footer__location-icon" />
                  </figure>
                  <a class="text text-decoration-none" href="tel:+1-543-123-4567" aria-label="llamar al +1-543-123-4567">
                    +1-543-123-4567
                  </a>
                </div>
                <div class="d-flex align-items-center">
                  <figure class="m-0 mr-4">
                    <img src="@/assets/images/icon-email.svg" alt="icon location" class="footer__location-icon" />
                  </figure>
                  <a class="text m-0 text-decoration-none" href="mailto:example@fylo.com">example@fylo.com</a>
                </div>
              </address>
            </div>
            <div class="col-12 col-lg-3">
              <div class="row">
                <div class="col-12 col-lg-6 mt-5 mt-lg-0">
                  <ul class="m-0 p-0 list-unstyled">
                    <li class="pb-3"><a href="#About" class="footer__link text">About Us</a></li>
                    <li class="pb-3"><a href="#Jobs" class="footer__link text">Jobs</a></li>
                    <li class="pb-3"><a href="#Press" class="footer__link text">Press</a></li>
                    <li class="pb-3"><a href="#Blog" class="footer__link text">Blog</a></li>
                  </ul>
                </div>
                <div class="col-12 col-lg-6 mt-5 mt-lg-0">
                  <ul class="m-0 p-0 list-unstyled">
                    <li class="pb-3"><a href="#Contact" class="footer__link text">Contact Us</a></li>
                    <li class="pb-3"><a href="#Terms" class="footer__link text">Terms</a></li>
                    <li class="pb-3"><a href="#Privacy" class="footer__link text">Privacy</a></li>
                  </ul>
                </div>
              </div>
            </div>
            <div class="col-12 col-lg-2 ">
              <div class="d-flex align-items-center justify-content-center justify-content-lg-start">
                <div class="footer__social-network">
                  <svg class="footer__social-network-svg" version="1.1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32 32">
                  <title>facebook</title>
                  <path  d="M19 6h5v-6h-5c-3.86 0-7 3.14-7 7v3h-4v6h4v16h6v-16h5l1-6h-6v-3c0-0.542 0.458-1 1-1z"></path>
                  </svg>
                </div>
                <div class="footer__social-network">
                  <svg class="footer__social-network-svg" version="1.1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32 32">
                  <title>instagram</title>
                  <path  d="M16 2.881c4.275 0 4.781 0.019 6.462 0.094 1.563 0.069 2.406 0.331 2.969 0.55 0.744 0.288 1.281 0.638 1.837 1.194 0.563 0.563 0.906 1.094 1.2 1.838 0.219 0.563 0.481 1.412 0.55 2.969 0.075 1.688 0.094 2.194 0.094 6.463s-0.019 4.781-0.094 6.463c-0.069 1.563-0.331 2.406-0.55 2.969-0.288 0.744-0.637 1.281-1.194 1.837-0.563 0.563-1.094 0.906-1.837 1.2-0.563 0.219-1.413 0.481-2.969 0.55-1.688 0.075-2.194 0.094-6.463 0.094s-4.781-0.019-6.463-0.094c-1.563-0.069-2.406-0.331-2.969-0.55-0.744-0.288-1.281-0.637-1.838-1.194-0.563-0.563-0.906-1.094-1.2-1.837-0.219-0.563-0.481-1.413-0.55-2.969-0.075-1.688-0.094-2.194-0.094-6.463s0.019-4.781 0.094-6.463c0.069-1.563 0.331-2.406 0.55-2.969 0.288-0.744 0.638-1.281 1.194-1.838 0.563-0.563 1.094-0.906 1.838-1.2 0.563-0.219 1.412-0.481 2.969-0.55 1.681-0.075 2.188-0.094 6.463-0.094zM16 0c-4.344 0-4.887 0.019-6.594 0.094-1.7 0.075-2.869 0.35-3.881 0.744-1.056 0.412-1.95 0.956-2.837 1.85-0.894 0.888-1.438 1.781-1.85 2.831-0.394 1.019-0.669 2.181-0.744 3.881-0.075 1.713-0.094 2.256-0.094 6.6s0.019 4.887 0.094 6.594c0.075 1.7 0.35 2.869 0.744 3.881 0.413 1.056 0.956 1.95 1.85 2.837 0.887 0.887 1.781 1.438 2.831 1.844 1.019 0.394 2.181 0.669 3.881 0.744 1.706 0.075 2.25 0.094 6.594 0.094s4.888-0.019 6.594-0.094c1.7-0.075 2.869-0.35 3.881-0.744 1.050-0.406 1.944-0.956 2.831-1.844s1.438-1.781 1.844-2.831c0.394-1.019 0.669-2.181 0.744-3.881 0.075-1.706 0.094-2.25 0.094-6.594s-0.019-4.887-0.094-6.594c-0.075-1.7-0.35-2.869-0.744-3.881-0.394-1.063-0.938-1.956-1.831-2.844-0.887-0.887-1.781-1.438-2.831-1.844-1.019-0.394-2.181-0.669-3.881-0.744-1.712-0.081-2.256-0.1-6.6-0.1v0z"></path>
                  <path  d="M16 7.781c-4.537 0-8.219 3.681-8.219 8.219s3.681 8.219 8.219 8.219 8.219-3.681 8.219-8.219c0-4.537-3.681-8.219-8.219-8.219zM16 21.331c-2.944 0-5.331-2.387-5.331-5.331s2.387-5.331 5.331-5.331c2.944 0 5.331 2.387 5.331 5.331s-2.387 5.331-5.331 5.331z"></path>
                  <path  d="M26.462 7.456c0 1.060-0.859 1.919-1.919 1.919s-1.919-0.859-1.919-1.919c0-1.060 0.859-1.919 1.919-1.919s1.919 0.859 1.919 1.919z"></path>
                  </svg>
                </div>
                <div class="footer__social-network">
                  <svg class="footer__social-network-svg" version="1.1" xmlns="http://www.w3.org/2000/svg"  viewBox="0 0 32 32">
                  <title>twitter</title>
                  <path  d="M32 7.075c-1.175 0.525-2.444 0.875-3.769 1.031 1.356-0.813 2.394-2.1 2.887-3.631-1.269 0.75-2.675 1.3-4.169 1.594-1.2-1.275-2.906-2.069-4.794-2.069-3.625 0-6.563 2.938-6.563 6.563 0 0.512 0.056 1.012 0.169 1.494-5.456-0.275-10.294-2.888-13.531-6.862-0.563 0.969-0.887 2.1-0.887 3.3 0 2.275 1.156 4.287 2.919 5.463-1.075-0.031-2.087-0.331-2.975-0.819 0 0.025 0 0.056 0 0.081 0 3.181 2.263 5.838 5.269 6.437-0.55 0.15-1.131 0.231-1.731 0.231-0.425 0-0.831-0.044-1.237-0.119 0.838 2.606 3.263 4.506 6.131 4.563-2.25 1.762-5.075 2.813-8.156 2.813-0.531 0-1.050-0.031-1.569-0.094 2.913 1.869 6.362 2.95 10.069 2.95 12.075 0 18.681-10.006 18.681-18.681 0-0.287-0.006-0.569-0.019-0.85 1.281-0.919 2.394-2.075 3.275-3.394z"></path>
                  </svg>
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
      padding-top: 150px;
      padding-bottom: 30px;
      background-color: $DarkBlueFooter;
      &__location-description{
        font-size: .95rem;
        padding-right: 4rem;
      }
      &__location-icon {
        width: 1rem;
      }
      &__link {
        text-decoration: none;
        font-size: .95rem;
        &:hover {
          color: $White;
          font-weight: 400;
        }
      }
      &__social-network{
        width: 32px;
        height: 32px;
        border-radius: 50%;
        border: 1px solid $Gray;
        display: flex;
        align-items: center;
        justify-content: center;
        &:not(:last-child){
          margin-right: 1rem;
        }
        &:hover {
          border-color: $Cyan ;
          .footer__social-network-svg {
            fill: $Cyan;
          }
        }
      }  
      &__social-network-svg{
        fill: $White;
        width: 15px;
        height: 15px;
      }
  }
  @media screen and ( min-width: $media_lg ) {
    .footer { 
      &__location-description {
        padding-right: 2rem;
      }
    }
  }
</style>