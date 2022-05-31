<template>
  <div class="ProgressBar">
    <v-progress-linear
      value="100"
      :color="randomColor()"
      height="10"
    ></v-progress-linear>
  </div>
</template>

<style scoped></style>
<script>
export default {
  data: () => ({
    randomColor() {
      let colors = ["red", "purple", "green", "blue", "yellow", "orange"];
      return colors[Math.floor(Math.random() * colors.length)];
    },
  }),
};
</script>
