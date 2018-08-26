<template>
  <section class="section">
    <div class="container content">
      <div class="columns">
        <div class="column is-half">
          <h2 class="title">Who am I?</h2>

          <p>
            I am a 21 year old Software Engineer who has a passion for
            designing and creating web-based applications that can work
            in a variety of environments, whether that be on a convential
            desktop or on more mobile devices, like phones or tablets.
          </p>

          <p>
            I attended UA Little Rock where I completed my degree in Information
            Science in only three years, while working at Delta Plastics of the
            South as a Software Engineer creating and/or maintaining three
            production level applications, along with doing other IT level
            functions.
          </p>
        </div>

        <div class="column is-half">
          <h2 class="title">What do I do?</h2>

          <img src="http://pipeplanner.com/Content/images/DeltaPlastics200.png" class="image is-pulled-right">

          <p>
            Currently I work at Delta Plastics of the South as a Software
            Engineer. As a company we are focused on providing our customers
            with ways to ensure they can recycle their plastic products in a
            way that is respectable and friendly to the environment.
          </p>

          <p>
            I have worked with many departments building software that helped
            achieve our recycling efforts, along with ensuring water
            conservation within the greater Mississippi River Delta Region.
            These efforts have helped divert 13,000,000 pounds of plastic from
            landfills and helped conserve more than 4,000,000,000 gallons of
            water.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component
export default class LandingAbout extends Vue {}
</script>

<style lang="scss" scoped>
  .image.is-pulled-right {
    margin: 0 0 1rem 1rem;
  }
</style>
