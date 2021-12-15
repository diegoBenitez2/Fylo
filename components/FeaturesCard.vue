<template>
  <article class="card-features text-center">
    <figure class="card-features__logo-container">
      <img :src="`@/assets/images/${card.logo}`" :alt="card.title" class="card-features__logo">
    </figure>
    <h4 class="card-features__title title mb-3">{{card.title}}</h4>
    <p class="card-features__text text text-center px-5">
      {{card.text}}
    </p>
  </article>
</template>

<script>
  export default {
    name: 'FeaturesCard',
    props: {
      card: {
        type: Object,
        default: () => {},
      }
    }
  }
</script>

<style lang="scss" scoped>
  .card-features {
    &__logo-container {
      margin: 0 0 2rem 0;
      width: 100px;
      height: 100px;
    }
    &__logo {
      object-fit: contain;
      width: 100%;
      height: 100%;
    }
    &__title{
      font-size: 1.2rem;
    }
  }
</style>