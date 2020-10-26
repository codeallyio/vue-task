<template>
  <div class="element-value-container">
    <div class="element">
      {{ element }}
    </div>
    <div class="value">
      {{ value }}
    </div>
  </div>
</template>

<script>
export default {
  name: "ElementValue",
  props: {
    element: String,
    value: String,
  },
};
</script>

<style scoped>
.element-value-container {
  height: 60px;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
}

.element {
  color: gray;
}
</style>