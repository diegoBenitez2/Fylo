<template>
  <ul class="nav justify-content-end">
    <li class="nav-item nav__item "><a href="#" class="nav-link active text"> Features</a></li>
    <li class="nav-item nav__item"><a href="#" class="nav-link text">Team</a></li>
    <li class="nav-item nav__item"><a href="#" class="nav-link text">Sign In</a></li>
  </ul>
</template>

<script>
  export default {
    name: 'Nav',
  }
</script>

<style lang="scss">
  .nav {
    &__item .nav-link:hover {
      text-decoration: underline;
      color: $White;
    }
  }
</style>