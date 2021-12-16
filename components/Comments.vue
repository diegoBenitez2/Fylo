<template>
  <section class="comments pt-5 mt-5">
    <div class="container d-flex flex-column justify-content-center position-relative">
      <div class="row justify-content-center comments__list-comments">
          <div class="col-auto col-md-4 position-relative" v-for="(comment, index) in comments" :key="index">
            <CommentsCard :comment="comment" />
          </div>
      </div>
      <div class="row">
        <div class="col-12 col-lg-9 mx-auto">
          <div class="comments__form text-center px-3 px-md-5">
            <h2 class="title comments__title text-center mb-4">
              Get early access today
            </h2>
            <p class="text comments__text text-center">
              It only takes a minute to sign up and our free starter tier is extremely generous. If you have any questions, our support team would be happy to help you.
            </p>
            <div class="col-12">
              <div class="row">
                <div class="col-12 col-md-8">
                  <InputFylo />
                </div>
                <div class="col-12 col-md-4 mb-4">
                  <BtnFylo text="Get Started For Free" :sizeFixed="false" />
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>      
    </div>
  </section>
</template>

<script>
  export default {
    name: 'Comments',
    data(){
      return {
        comments: [
          {
            text: 'Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-oiled collaboration machine.',
            user: {
              name: 'Satish Patel',
              rol: 'Founder & CEO, Huddle',
              avatar: '@/assets/images/profile-1.jpg',
            },
            
          },
          {
            text: 'Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-oiled collaboration machine.',
            user: {
              name: 'Bruce McKenzie',
              rol: 'Founder & CEO, Huddle',
              avatar: '@/assets/images/profile-2.jpg',
            },
            
          },
          {
            text: 'Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-oiled collaboration machine.',
            user: {
              name: 'Iva Boyd',
              rol: 'Founder & CEO, Huddle',
              avatar: '@/assets/images/profile-3.jpg',
            },
            
          },
        ]
      }
    }
  }
</script>

<style lang="scss" scoped>
  .comments {
    &__list-comments{
      margin: 0px 0 100px;
      &::before {
        content: '';
        display: block;
        position: absolute;
        z-index: -1;
        background-image: url('@/assets/images/bg-quotes.png');
        background-repeat: no-repeat;
        background-size: contain;
        width: 30px;
        height: 30px;
        top: -10px;
        left: 0;
      }
    }
    &__form {
      padding-top: 30px;
      min-width: 300px;
      display: flex;
      flex-direction: column;
      align-items: center ;
      background-color: $DarkBlueMain ;
      border-radius: .5rem;
      box-shadow: 3px 3px 5px 3px  rgba($color: #000, $alpha: .3);
    }
    &__text {
      margin-bottom: 30px;
    }
  }
  @media screen and (min-width: $media_md) {
    .comments {
      &__text {
        padding: 0px 50px;
      }
      &__list-comments::before {
        width: 45px;
        height: 45px;
        top: -20px;
        left: 15px;
      }
    }
  }
</style>