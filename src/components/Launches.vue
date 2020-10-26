<template>
  <div>
    <h1 id="launches-title">SpaceX Launches</h1>
    <div id="launches-container">
      <div class="launch-box" v-for="(launch, x) in launchesData" :key="x">
        <ElementValue
          v-bind:element="'Mission name'"
          v-bind:value="launch.mission_name"
        />
        <ElementValue
          v-bind:element="'Rocket name'"
          v-bind:value="launch.rocket_name"
        />
      </div>
    </div>
  </div>
</template>

<script>
import launchesData from "../assets/data-set";
import ElementValue from "./ElementValue";

export default {
  name: "Launches",
  components: {
    ElementValue,
  },
  data() {
    return {
      launchesData,
    };
  },
};
</script>

<style scoped>
#launches-title {
  color: forestgreen;
}

#launches-container {
  color: #000;
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.launch-box {
  width: 90%;
  min-width: 300px;
  max-width: 800px;
  border: solid black 1px;
  margin: 5px;
}
</style>