<template>
  <div id="projects" class="background-alt">
    <h2 class="heading">Projects</h2>
    <div class="container">
      <div class="row">
        <div class="col-12">
          <Romoni></Romoni>
        </div>
      </div>
      <div class="row">
        <div class="col-12">
          <Romoni></Romoni>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Romoni from "./Romoni";

export default {
  name: "Projects",
  components: { Romoni },
};
</script>

<style scoped>
#projects {
  padding: 50px 15px;
  border-bottom: 1px solid #dcd9d9;
  text-align: center;
}
</style>
