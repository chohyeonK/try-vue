<template>
  <div class="home">
    <PartWeather />
  </div>
</template>

<script>
// @ is an alias to /src
import PartWeather from "@/components/PartWeather.vue";

export default {
  name: "HomeView",
  components: {
    PartWeather,
  },
};
</script>
