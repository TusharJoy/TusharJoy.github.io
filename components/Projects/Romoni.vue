<template>
  <div class="project shadow-large">
    <div class="project-image">
      <img src="images/romoni.jpeg" />
    </div>
    <!-- End .project-image -->
    <div class="project-info">
      <h3>Romoni</h3>
      <p class=text-left>
        Romoni is one of the largest on demand beauty services of the
        country promoting women empowerment.
        <ul>
          <li>
            Designed, developed and optimized the whole system. Reduced human effort by 100%.
          </li>
          <li>
            Implemented real time service searching based on location, availability, skills and ratings.
          </li>
          <li>
            Wrote Rest APIs and documentation and also integrated payment gateway like Bkash.
          </li>
        </ul>
      </p>
      <a href="https://romoni.com.bd/" target="_blank">View Project</a>
    </div>
    <!-- End .project-info -->
  </div>
</template>

<script>
export default {
  name: "Romoni",
};
</script>

<style scoped>
.project {
  position: relative;
  max-width: 900px;
  margin: 0 auto 30px auto;
  overflow: hidden;
  background: #fff;
  border-radius: 4px;
}
</style>
