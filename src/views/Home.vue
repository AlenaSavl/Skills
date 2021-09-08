<template>
  <div class="white">
    <vHeader msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import vHeader from "@/components/vHeader.vue";

export default {
  name: "Home",
  components: {
    vHeader,
  },
};
</script>
