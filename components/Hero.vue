<template>
  <section class="hero container text-center">
    <div class="row">
      <div class="col-12 col-md-8 col-lg-6 mx-auto">
        <div class="row">
          <div class="col-12">
            <figure class="hero__image-container">
              <img class="hero__image mb-5" src="@/assets/images/illustration-intro.png" alt="hero imagen">
            </figure>
          </div>
          <div class="col-12">
            <h2 class="hero__title text-center title">All your files in one secure location, accessible anywhere.
            </h2>
          </div>
        </div>
        <div class="col-12 col-lg-11 mx-auto">
          <p class="hero__description text-center text px-4">
              Fylo stores all your most important files in one secure location. Access them wherever you need, share and collaborate with friends family, and co-workers.
          </p>
        </div>
      </div>
    </div>
    <BtnFylo />
  </section>
</template>

<script>
  export default {
    name: 'Hero'
  }
</script>

<style lang="scss" scoped>
.hero {
  &__image-container {
    margin: 0;
    width: 100%;
  }
  &__image{
    object-fit: contain;
    width: 100%;
    height: 100%;
  }
  &__description {
    font-size: 1.07rem;
    margin: 1.8rem 0 2.3rem;
  }
}
</style>