<script lang="ts">
export default {};
</script>

<template>
  <div class="content-container about">
    <h2 class="secondary-m normal f45 center mobile-text">
      <span class="heading-dot">.</span>About
    </h2>
    <p class="primary-l accent f20 center mobile-text">
      Hello, I’m Erik Arens a frontend developer from Germany. I always loved to
      create my own things and to solve problems, so I decided to focus on web
      development. I think that web development is a core feature of nearly any
      industry.
    </p>
    <br />
    <p class="primary-l accent f20 center mobile-text">
      Due to my side hustle "Netzhero" I already had a few projects where I had
      to work in a team and communicate with the Back-End of a Web-Application.
      Therefore, I know how to combine my obtained skills to bring value to a
      project.
    </p>
    <div class="tech-stack-container">
      <img
        src="../assets/images/js.png"
        alt="Tech Stack JavaScript"
        class="stack"
        width="135"
        height="135"
      />
      <img
        src="../assets/images/angular.png"
        alt="Tech Stack Angular 2+"
        class="stack-extra"
        width="250"
        height="250"
      />
      <img
        src="../assets/images/ts.png"
        alt="Tech Stack TypeScript"
        class="stack"
        width="135"
        height="135"
      />
    </div>
  </div>
</template>

<style>
.tech-stack-container {
  display: flex;
  justify-content: center;
  align-items: center;
}

@media screen and (max-width: 600px) {
  .about {
    margin-top: 130px;
  }

  .stack {
    width: 70px;
    height: 70px;
  }
  .stack-extra {
    width: 130px;
    height: 130px;
  }
}
</style>
