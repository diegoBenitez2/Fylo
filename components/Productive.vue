<template>
  <section class="productive">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-12 col-lg-6 my-4">
          <figure class="productive__image-container">
            <img src="@/assets/images/illustration-stay-productive.png" alt="cover image" class="productive__image" />
          </figure>
        </div>
        <div class="col-12 col-lg-6">
          <h4 class="title productive__title mb-4">
            Stay productive, wherever you are
          </h4>
          <p class="text productive__text  mb-4">
            Never let location be an issue when accessing your files. Fylo has you covered for all of your file 
            storage needs.
          </p>
          <p class=" text productive__text">
            Securely share files and folders with friends, family and colleagues for live collaboration. No email 
            attachments required.
          </p>
          <a  class="text productive__link" href="#" aria-label="See how Fylo works">
            See how Fylo works
            <img src="@/assets/images/icon-arrow.svg" alt="arrow right icon" class="productive__arrow-left">
          </a>
        </div>
    </div>
    </div>
  </section>
</template>

<script>
  export default {
    name: 'Productive'
  }
</script>

<style lang="scss">
  .productive {
    margin-top: 40px;
    &__image{
      object-fit: contain;
      width: 100%;
      height: 100%;
    }
    &__title {
      font-size: 1.3rem;
    }
    &__link:hover {
      text-decoration: underline;
      color: $Cyan;
    }
  }
  @media screen and (min-width: $media_lg) {
    .productive {
      &__title {
        font-size: 2.8rem;
        padding-right: 4rem;
      }
    }
  }
</style>