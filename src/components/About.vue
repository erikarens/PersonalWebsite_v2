<script lang="ts">
export default {};
</script>

<template>
  <div class="content-container about">
    <h2 class="secondary-m normal f45 center mobile-text">
      <span class="heading-dot">.</span>About <span class="mobile-line"></span>
    </h2>
    <img src="../assets/images/erikarens.jpg" alt="" class="personal-img" />
    <p class="primary-l accent f20 center mobile-text">
      Software Developer with 3+ years of experience specializing in Angular,
      React Native, and ASP.Net. I thrive on tackling challenging projects and
      leveraging my skills to create innovative solutions. While most of my work
      has been on private projects, I have gained valuable expertise in building
      business applications.
    </p>

    <br />
    <p class="primary-l accent f20 center mobile-text">
      My goal is to become a specialist in Software Engineering and contribute
      to significant projects that can shape the future. I am particularly
      interested in the exciting field of Machine Learning and its potential to
      revolutionize industries.
    </p>

    <br />
    <p class="primary-l accent f20 center mobile-text">
      As a fast learner, I quickly adapt to new technologies and methodologies,
      allowing me to stay ahead in the ever-evolving software development
      landscape. I am known for my collaborative approach, working effectively
      within teams to achieve common goals. My enthusiasm and motivation drive
      me to deliver high-quality results.
    </p>

    <br />
    <p class="primary-l accent f20 center mobile-text">
      Let’s connect and explore opportunities to collaborate on exciting
      projects that push the boundaries of software development!
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

.personal-img {
  border: 4px solid #1b2741;
  border-radius: 50%;
  width: 150px;
  display: block;
  margin-left: auto;
  margin-right: auto;
  margin-top: 25px;
  margin-bottom: 25px;
}

a.normal-link {
  color: #c6c8cd;
  font-family: primary-r;
  transition: all 0.4s;
  display: inline-block;
}
a.normal-link:hover {
  transition: all 0.3s ease-out;
  transform: scale(1.1);
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
