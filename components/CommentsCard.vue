<template>
    <article class="comments-card">
      <p class="comments-card__comment text">
          {{ comment.text }}
      </p>
      <UserInfo :user="comment.user" />
    </article>
</template>

<script>
  export default {
    name: 'CommentsCard',
    props: {
      comment: {
        type: Object,
        default: () => {},
      },
    },
  }
</script>

<style lang="scss" scoped>
  .comments-card {
    background-color: $DarkBlueBack ;
    box-shadow: 3px 6px 6px rgba($color: #000, $alpha: .3);
    padding: 30px 20px 10px;
    border-radius: .3rem;
    margin: 10px 20px;
    max-width: 280px ;
    &__comment {
      font-size: .8rem;
    }
  }
  @media screen and (min-width:$media_xl) {
    .comments-card {
      max-width: 320px;
      &__comment {
        font-size: 1rem;
      }
    }
  }
</style>