<template>
    <div class="input mb-4">
      <input type="email" name="email" placeholder="email@example.com" class="input__text"/>
      <span class="text-danger input__error ml-4 text-left">
        Please enter a valid email address
      </span>
    </div>
</template>

<script>
  export default {
    name: 'InputFylo',
  }
</script>

<style lang="scss" scoped>
  .input {
    text-align: left;
    &__text {
      width: 100%;
      display: block;
      padding: 12px 20px;
      border: 0;
      background-color: $White;
      border-radius: 2.5rem;
      font-size: 1rem;
      color: $DarkBlueIntro ;
      &::placeholder {
        color: $Gray ;
      }
    }
    &__error{
      font-size: .7rem;
      font-weight: 700;
    }
  }
</style>