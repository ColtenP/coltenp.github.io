<template>
  <section class="section">
    <div class="container">
      <h2 class="title">Education, Awards, &amp; Skills</h2>

      <div class="columns">
        <div class="column">
          <h3 class="title is-4">Education</h3>

          <section class="section content">
            <h3 class="title is-4 is-marginless">UA Little Rock</h3>
            <h4 class="subtitle is-5 is-marginless">
              Bachelors of Science in Information Science - <small>Little Rock, AR</small>
            </h4>
            <small class="subtitle is-6">August 2015 - July 2018</small>

            <ul>
              <li>Graduated with Magna Cum Laude - 3.89 GPA</li>
              <li>Recieved Deans List Every Semester of Attendance</li>
            </ul>
          </section>

          <section class="section content">
            <h3 class="title is-4 is-marginless">Texas A&amp;M</h3>
            <h4 class="subtitle is-5 is-marginless">
              General Education - <small>Texarkana, Texas</small>
            </h4>
            <small class="subtitle is-6">August 2015 - July 2018</small>

            <ul>
              <li>
                Completed 24 College Credit Hours in the place of
                senior year of High School
              </li>
            </ul>
          </section>

          <h3 class="title is-4">Awards</h3>

          <section class="section content">
            <h3 class="title is-4 is-marginless">Dean's Academic Merit</h3>
            <small class="subtitle is-6">August 2015 - July 2018</small>

            <p>
              The Dean's Academic Merit scholarship is awarded to incoming
              freshmen who have a cumulative high school GPA of 3.25, and at
              least a 26 on the ACT
            </p>
          </section>

          <section class="section content">
            <h3 class="title is-4 is-marginless">EIT Academic Scholarship</h3>
            <small class="subtitle is-6">August 2015 - July 2018</small>

            <p>
              The EIT Academic Scholarship is awarded to incoming freshmen
              who show a passion for STEM based majors, and have at least
              a 25 on the ACT, and a cumulative high school GPA of 3.0
            </p>
          </section>

          <section class="section content">
            <h3 class="title is-4 is-marginless">UA Little Rock Dean's List</h3>

            <p>
              Awarded for upholding a GPA of at least 3.8 for the semesters of:
              Fall 2015, Spring 2016, Fall 2016, Spring 2017, Fall 2017, and
              Spring 2018
            </p>
          </section>

          <section class="section content">
            <h3 class="title is-4 is-marginless">Outstanding Freshman Academic Achievement Award</h3>
            <small class="subtitle is-6">Fall 2015, Spring 2016</small>
          </section>
        </div>

        <div class="column">
          <h3 class="title is-4">Spoken Languages</h3>
          <div class="content">
            <ul>
              <li>English - Native</li>
              <li>Swedish - Fluent</li>
            </ul>
          </div>

          <h3 class="title is-4">Programming Languages</h3>
          <div class="content">
            <ul>
              <li>JavaScript - Advanced - 5 years</li>
              <li>TypeScript - Advanced - 2 years</li>
              <li>C# - Intermediate - 4 years</li>
              <li>PHP - Advanced - 6 years</li>
              <li>Java - Intermediate - 6 years</li>
            </ul>
          </div>

          <h3 class="title is-4">Tools &amp; Skills</h3>
          <div class="content">
            <ul>
              <li>Linux Management - 6 years</li>
              <li>Laravel - 4 years</li>
              <li>Node.js - 4 years</li>
              <li>Vue.js - 3 years</li>
              <li>React - 1 year</li>
              <li>SASS - 2 years</li>
              <li>LESS - 3 years</li>
              <li>Webpack - 3 years</li>
              <li>Azure - 2 years</li>
              <li>AWS - 1 year</li>
              <li>G Suite - 5 years</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component
export default class LandingEducation extends Vue {}
</script>
