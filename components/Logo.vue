<template>
<figure class="logo">
  <img class="logo__svg" src="@/assets/images/logo.svg" alt="logo">
</figure>
</template>
<script>
export default {
  name:'Logo',
}
</script>
<style lang="scss">
.logo {
	width: 25%; 
	overflow: hidden; 
  margin: 0;
  &__svg {
    max-width: 100%;
    object-fit: contain;
  }
}
</style>
