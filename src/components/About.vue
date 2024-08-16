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
      I’m a Software Developer with a passion for solving complex problems and building practical solutions. My expertise spans across .NET, Angular, React Native, and TypeScript, with experience in both front-end and back-end development. I’ve worked extensively with frameworks like Entity Framework Core and NestJS, and I’m comfortable with styling tools like Bootstrap and Tailwind CSS.
    </p>

    <br />
    <p class="primary-l accent f20 center mobile-text">
      Much of my experience comes from developing business applications through private projects, where I’ve enjoyed digging deep into code to optimize performance and create efficient solutions. I’m also familiar with tools like TypeORM, Coolify, and managing VPS.
    </p>

    <br />
    <p class="primary-l accent f20 center mobile-text">
      I’m always eager to learn and excited about tackling new challenges, whether it’s exploring new technologies or refining my skills in existing ones
    </p>

    <br />
    <p class="primary-l accent f20 center mobile-text">
      Let’s connect and explore opportunities to collaborate on exciting
      projects that push the boundaries of software development!
    </p>

    <!-- <div class="tech-stack-container"> -->
    <!--   <img -->
    <!--     src="../assets/images/js.png" -->
    <!--     alt="Tech Stack JavaScript" -->
    <!--     class="stack" -->
    <!--     width="135" -->
    <!--     height="135" -->
    <!--   /> -->
    <!--   <img -->
    <!--     src="../assets/images/angular.png" -->
    <!--     alt="Tech Stack Angular 2+" -->
    <!--     class="stack-extra" -->
    <!--     width="250" -->
    <!--     height="250" -->
    <!--   /> -->
    <!--   <img -->
    <!--     src="../assets/images/ts.png" -->
    <!--     alt="Tech Stack TypeScript" -->
    <!--     class="stack" -->
    <!--     width="135" -->
    <!--     height="135" -->
    <!--   /> -->
    <!-- </div> -->
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
