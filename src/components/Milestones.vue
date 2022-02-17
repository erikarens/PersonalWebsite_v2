<script lang="ts">
export default {};
</script>

<template>
  <div class="milestone-container">
    <h2 class="secondary-m normal f45 center mobile-text">
      <span class="heading-dot">.</span>Milestones <span class="mobile-line milestone"></span>
    </h2>

    <div class="timeline">
      <div class="container left">
        <h2 class="secondary-l accent f20 timestamp">January, 2022</h2>
        <div class="content project">
          <h3 class="secondary-m normal f30 mobile-heading"><span class="heading-dot">.</span>Customer Map</h3>
          <p class="primary-l accent f20">
            A map that hold all kind of information about customers to plan routes for their sales team.
          </p>
          <a href="https://github.com/erikarens/CustomerMap" target="_blank" class="project-link"
            >Customer Map Github</a
          >
        </div>
      </div>

      <div class="container right">
        <h2 class="secondary-l accent f20 timestamp">January, 2022</h2>
        <div class="content">
          <h3 class="secondary-m normal f30 mobile-heading"><span class="heading-dot">.</span>Angular Training</h3>
          <p class="primary-l accent f20">
            To get better with Angular, I started an online training and got myself in some Angular projects to learn
            more.
          </p>
        </div>
      </div>

      <div class="container left">
        <h2 class="secondary-l accent f20 timestamp">January, 2022</h2>
        <div class="content">
          <h3 class="secondary-m normal f30 mobile-heading"><span class="heading-dot">.</span>Advanced Training</h3>
          <p class="primary-l accent f20">
            Finished my advanced training with a grade of 1,2 and acquired a diploma with the title "Certified
            Web-Developer" (Geprüfter Web-Entwickler)
          </p>
        </div>
      </div>

      <div class="container right">
        <h2 class="secondary-l accent f20 timestamp">December, 2021</h2>
        <div class="content project">
          <h3 class="secondary-m normal f30 mobile-heading"><span class="heading-dot">.</span>Produktfinder</h3>
          <p class="primary-l accent f20">
            A product calculator, to help the customer find the right product for his needs.
          </p>
          <a href="https://github.com/erikarens/produktfinder" target="_blank" class="project-link">Produktfinder</a>
        </div>
      </div>

      <div class="container left">
        <h2 class="secondary-l accent f20 timestamp">February, 2021</h2>
        <div class="content">
          <h3 class="secondary-m normal f30 mobile-heading"><span class="heading-dot">.</span>Advanced Training</h3>
          <p class="primary-l accent f20">
            Started an advanced training to get a professional qualification "Certified Web-Developer" (Geprüfter
            Web-Entwickler).
          </p>
        </div>
      </div>

      <div class="container right">
        <h2 class="secondary-l accent f20 timestamp">January, 2019</h2>
        <div class="content">
          <h3 class="secondary-m normal f30 mobile-heading"><span class="heading-dot">.</span>Founded Netzhero</h3>
          <p class="primary-l accent f20">
            Founded Netzhero as a side hustle to pursue my passion (Web-Development Business)
          </p>
          <a href="https://netzhero.de" target="_blank" class="project-link">Netzhero</a>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.milestone-container {
  margin: 300px 0;
}

a.project-link {
  text-decoration: none;
  color: #ffb800;
  transition: all 0.4s;
}
a:hover.project-link {
  transition: all 0.4s;
  text-shadow: 2px 2px 8px #ffb800;
}

.timestamp {
  margin-left: 20px;
}

/* The actual timeline (the vertical ruler) */
.project {
  border: 0.5px solid #ffb800;
}

.timeline {
  position: relative;
  max-width: 1200px;
  margin: 80px auto;
}

/* The actual timeline (the vertical ruler) */
.timeline::after {
  content: '';
  position: absolute;
  width: 1px;
  background-color: #616a77;
  top: 0;
  bottom: 0;
  left: 50%;
  margin-left: -3px;
}

/* Container around content */
.container {
  padding: 10px 40px;
  position: relative;
  background-color: inherit;
  width: 50%;
}

/* The circles on the timeline */
.container::after {
  content: '';
  position: absolute;
  width: 21px;
  height: 21px;
  right: -8px;
  background-color: #1d303b;
  border: 1px solid #616a77;
  top: 15px;
  border-radius: 50%;
  z-index: 1;
}

/* Place the container to the left */
.left {
  left: 0;
}

/* Place the container to the right */
.right {
  left: 50%;
}

/* Fix the circle for containers on the right side */
.right::after {
  left: -13px;
}

/* The actual content */
.content {
  padding: 20px 30px;
  background-color: #283446;
  position: relative;
  border-radius: 12px;
}

/* Media queries - Responsive timeline on screens less than 600px wide */
@media screen and (max-width: 600px) {
  .milestone-container {
    margin: 100px 0 150px 0;
  }

  .timeline {
    margin: 30px auto;
  }

  .mobile-heading {
    line-height: 130%;
    margin-bottom: 10px;
  }

  /* Place the timelime to the left */
  .timeline::after {
    left: 31px;
  }

  /* Full-width containers */
  .container {
    width: 100%;
    padding-left: 70px;
    padding-right: 25px;
  }

  /* Make sure all circles are at the same spot */
  .left::after,
  .right::after {
    left: 18px;
  }

  /* Make all right containers behave like the left ones */
  .right {
    left: 0%;
  }
}
</style>
