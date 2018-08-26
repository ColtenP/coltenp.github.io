<template>
  <div class="landing-hero hero is-success is-large has-text-shadow">
    <div class="container">
      <div class="hero-body has-text-right">
        <h1 class="title is-1">
          Colten Pilgreen
        </h1>
        <h2 class="subtitle is-3 has-text-white">
          Ecoloving Software Engineer in Little Rock, AR
        </h2>
      </div>
    </div>
    <div class="triangle"></div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component
export default class LandingHero extends Vue {}
</script>

<style lang="scss" scoped>
  .landing-hero {
    background-image: url('/assets/img/hero.jpg');
    background-position: center center;
    background-size: cover;
    overflow: hidden;

    .triangle {
      width: 0;
      height: 0;
      border-style: solid;
      border-width: 0 0 10vh 100vw;
      border-color: transparent transparent #ffffff transparent;
    }
  }
</style>
