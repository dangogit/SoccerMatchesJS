<template>
  <div class="container">
    <h1 class="title">Team Page</h1>
    <TeamFullDetails ></TeamFullDetails>
  </div>
</template>

<script>
import TeamFullDetails from "../components/TeamFullDetails";
export default {
  components: {
    TeamFullDetails, 
  }
};
</script>

<style lang="scss" scoped>
.RandomRecipes {
  margin: 10px 0 10px;
}
.blur {
  -webkit-filter: blur(5px); /* Safari 6.0 - 9.0 */
  filter: blur(2px);
}
::v-deep .blur .recipe-preview {
  pointer-events: none;
  cursor: default;
}
</style>