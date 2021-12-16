<template>
  <article class="user-information mt-4">
    <div class="d-flex align-items-center">
      <figure class="user-information__avatar-container m-0">
        <img :src="user.avatar" :alt="`${user.name} avatar`" class="user-information__avatar" />
      </figure>
        <div class="ml-2">
          <h6 class="user-information__name  title mb-1">
            {{ user.name }}
          </h6>
          <p class="user-information__rol text">
            {{ user.rol }}
          </p>
        </div>
    </div>
  </article>
</template>

<script>
  export default {
    name: 'UserInfo',
    props: {  
      user: {
        type: Object,
        default: () => {},
      }
    }
  }
</script>

<style lang="scss" scoped>
  .user-information {
    width: 100%;
    &__avatar-container {
      width: 30px;
      height: 30px;
      border-radius: 50%;
    }
    &__avatar {
      width: 100%;
      height: 100%;
      object-fit: contain;
    }
    &__name {
      font-size: .8rem;
      font-weight: 700;
      margin-bottom: .5rem;
    }
    &__rol {
      font-size: .5rem;
    }
  }
</style>