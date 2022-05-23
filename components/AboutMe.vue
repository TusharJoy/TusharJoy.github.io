<template>
  <div>
    <div id="lead">
      <div id="lead-content">
        <h1>Tushar Ghosh Joy</h1>
        <h2>
          Software Engineer<a
            target="_blank"
            href="https://www.cefalo.com/"
            style="text: green"
            >@Cefalo</a
          >
        </h2>
        <a href="resume.pdf" class="btn-rounded-white">Download Resume</a>
      </div>
      <!-- End #lead-content -->

      <div id="lead-overlay"></div>

      <div id="lead-down">
        <span v-scroll-to="{ element: '#contact', duration: 4000 }">
          <i class="fa fa-chevron-down" aria-hidden="true"></i>
        </span>
      </div>
      <!-- End #lead-down -->
    </div>
    <!-- End #lead -->

    <div id="about">
      <div class="container">
        <div class="row">
          <div class="col-md-4">
            <h2 class="heading">About Me</h2>
          </div>
          <div class="col-md-8">
            <p>
              I am Experienced Software Engineer with a demonstrated history of
              working in the web technology and services industry. Skilled in
              PHP/Laravel, Vuejs, Express, Linux Servers, *nix environment.
              Strong engineering professional with a Bachelor of Science - B.Sc
              focused in Computer Science & Engineering from Khulna University
              of Engineering & Technology (KUET).
              <ul class="m-2">
                <li>
                  Technology I am playing
                withnow: TypeScript, Vue, Node/Express Docker, Kubernetes, Jest
                Asterisk, RabbitMQ, Apache Kafka
                </li>
                <li>Interest: - Large applications
                that Scales - Microservices and Distributed Systems
                </li>
              </ul>
            </p>
          </div>
        </div>
      </div>
    </div>
    <!-- End #about -->
  </div>
</template>

<script>
export default {
  name: "AboutMe",
  methods: {
    topToBottom() {},
  },
};
</script>

<style scoped>
</style>
