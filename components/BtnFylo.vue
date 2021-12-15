<template>
  <button class="btn-fylo text-center">
    {{ text }}
  </button>
</template>

<script>
  export default {
    name: 'BtnFylo',
    props: {
      text: {
        type: String,
        default: 'Get Started',
      }
    }
  }
</script>

<style lang="scss" scoped>
  .btn-fylo {
    border-radius: 2rem;
    padding: 15px 80px;
    border: 0;
    background:linear-gradient(120deg, $Cyan -40%, $Blue 100%) ;
    color: $White;
    font-size: 1rem;
    font-weight: 700;
    cursor: pointer;
    &:hover {
      background: linear-gradient(120deg, $White -90%, $Cyan 120%) ;
    }
  }
</style>