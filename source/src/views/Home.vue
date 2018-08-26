<template>
  <div>
    <Hero/>
    <About/>
    <Experience/>
    <Education/>
    <Contact/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

import Hero from '@/components/Landing/Hero.vue'
import About from '@/components/Landing/About.vue'
import Experience from '@/components/Landing/Experience.vue'
import Education from '@/components/Landing/Education.vue'
import Contact from '@/components/Landing/Contact.vue'

@Component({
  components: {
    Hero,
    About,
    Experience,
    Education,
    Contact
  }
})
export default class Home extends Vue {
  private isMenuOpen: boolean = false
}
</script>
