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
      Hello, I’m Erik Arens a frontend developer from Germany. I always loved to create my own things and to solve
      problems, so I decided to focus on web development. I think that web development is a core feature of nearly any
      industry.
    </p>

    <br />
    <p class="primary-l accent f20 center mobile-text">
      Due to my side hustle <a href="https://netzhero.de" target="_blank" class="normal-link">Netzhero</a> I already had
      a few projects where I had to work in a team and communicate with the Back-End of a Web-Application. Therefore, I
      know how to combine my obtained skills to bring value to a project.
    </p>
    <div class="tech-stack-container">
      <img src="../assets/images/js.png" alt="Tech Stack JavaScript" class="stack" width="135" height="135" />
      <img
        src="../assets/images/angular.png"
        alt="Tech Stack Angular 2+"
        class="stack-extra"
        width="250"
        height="250"
      />
      <img src="../assets/images/ts.png" alt="Tech Stack TypeScript" class="stack" width="135" height="135" />
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
