
<template>
  <div class="home">
    <section class="section-1">
      <b-container class="bv-example-row">
        <b-row>
          <b-col>
             <h1>Stay home.
            Skill up.</h1>
            <p>
              Build in-demand tech skills from home. Pluralsight gives technologists and teams the skills they need to move faster and deliver on their objectives.
            </p>
          </b-col>
          <b-col>
            <img  src="../assets/image/title-image.png">
          </b-col>
        </b-row>
      </b-container>
    </section>
    <skillcard/>
  </div>
</template>

<script>
// @ is an alias to /src
import skillcard from '@/components/skillcard.vue'

export default {
  name: 'Home',
  components: {
    skillcard
  }
}
</script>
<style scoped lang="scss">
.section-1{
  img{
    width: 100%;
  }
}
</style>

