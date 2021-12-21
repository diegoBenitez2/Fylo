<template>
  <section class="features">
    <div class="container">
      <div class="row justify-content-center">
        <div class="col-12 col-md-8 col-lg-6" v-for="(card, index) in features"     :key="index">
          <FeaturesCard :card="card"/>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
  export default {
    name: 'Features',
    data(){
      return {
        features :[
          {
            logo: 'icon-access-anywhere.svg',
            title: 'Access your files, anywhere',
            text: 'The ability to use a smartphone, tablet, or computer to access your account means your files follow you everywhere.'
          },
          {
            logo: 'icon-security.svg',
            title: 'Security you can trust',
            text: '2-factor authentication and user-controlled encryption are just a couple of the security features we allow to help secure your files.'
          },
          {
            logo: 'icon-collaboration.svg',
            title: 'Real-time collaboration',
            text: 'Securely share files and folders with friends, family and colleagues for live collaboration. No email attachments required.'
          },
          {
            logo: 'icon-any-file.svg',
            title: 'Store any type of file',
            text: ' Whether youre sharing holidays photos or work documents, Fylo has you covered allowing for all file types to be securely stored and shared.'
          },
        ]
      }
    }
  }
</script>

<style lang="scss" scoped>
  .features {
    margin: 130px 0 100px;
  }
</style>