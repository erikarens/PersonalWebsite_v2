<script lang="ts">
export default {};
</script>

<template>
  <div class="content-container header">
    <p class="lh-n primary primary-r f15">Hi, my name is</p>
    <h1 class="lh-n normal primary-b f60">Erik Arens</h1>
    <h2 class="lh-n accent primary-b f60">I'm a Software Developer.</h2>
    <p class="primary-l accent f20">
      I’m a Software Developer with a focus on .NET, Angular, and React Native. I enjoy working on challenging projects
      and using my skills to develop practical solutions. Most of my experience comes from private projects, where I’ve
      focused on building business applications.
    </p>
    <div class="cta-container">
      <a href="/#about" class="secondary-l cta f20 cta-spacing-rigth">Get to know me</a>
      <a href="https://github.com/erikarens" class="secondary-l accent f20 cta-spacing profile-cta"
        target="_blank">Github❯</a>
      <a href="https://www.linkedin.com/in/erik-arens-a48865195/" class="secondary-l accent f20 cta-spacing profile-cta"
        target="_blank">LinkedIn❯</a>
    </div>
  </div>
</template>

<style>
.cta-container {
  margin-top: 20px;
}

.cta-spacing-rigth {
  margin-right: 30px;
}

.cta-spacing {
  margin: 0 30px;
}

.profile-cta:hover {
  color: #ffb800;
  transition: all ease 0.5s;
}

@media screen and (max-width: 600px) {
  .header {
    margin-top: 160px;
  }

  .cta-container {
    display: flex;
    flex-wrap: wrap;
    text-align: center;
  }

  .cta-spacing-rigth {
    margin: 30px 20%;
  }

  .profile-cta {
    margin: 20px auto;
    text-align: center;
  }
}
</style>
