<template>
  <footer>
    <div class="container">
      <div class="row">
        <div class="col-sm-5 copyright">
          <p>Copyright © 2020 Tushar ghosh Joy</p>
        </div>
        <div class="col-sm-2 top">
          <span v-scroll-to="{ element: '#lead', duration: 4000 }">
            <i class="fa fa-chevron-up" aria-hidden="true"></i>
          </span>
        </div>

        <div class="col-sm-5 social">
          <ul>
            <li>
              <a href="https://github.com/TusharJoy" target="_blank"
                ><i class="fab fa-github"></i
              ></a>
            </li>
            <li>
              <a
                href="https://www.linkedin.com/in/tusharghoshjoy/"
                target="_blank"
                ><i class="fab fa-linkedin" aria-hidden="true"></i
              ></a>
            </li>
            <li>
              <a href="https://www.facebook.com/ragner.joy" target="_blank"
                ><i class="fab fa-facebook" aria-hidden="true"></i
              ></a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "HomeFooter",
};
</script>

<style scoped>
</style>
