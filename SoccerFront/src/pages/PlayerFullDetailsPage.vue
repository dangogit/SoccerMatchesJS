<template>
  <div class="container">
    <h1 class="title">Player Page</h1>
    <PlayePreview></PlayePreview>
    <PlayerFullDetails ></PlayerFullDetails>
  </div>
</template>

<script>
import PlayePreview from "../components/PlayePreview";
import PlayerFullDetails from "../components/PlayerFullDetails";
export default {
  components: {
    PlayePreview, 
    PlayerFullDetails, 
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