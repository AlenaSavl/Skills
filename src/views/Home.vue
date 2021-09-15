<template>
  <div class="white">
    <vHeader msg="Welcome to Your Vue.js App" />

    <b-container fluid class="lg p-4">
      <b-row>
        <b-col>
          <b-img
            thumbnail
            fluid
            :src="require('../assets/img/book.jpg')"
            alt=""
            width="200"
            height="200"
          ></b-img>
        </b-col>
        <b-col>
          <b-img
            thumbnail
            fluid
            :src="require('../assets/img/library.jpg')"
            alt=""
            width="200"
            height="200"
          ></b-img>
        </b-col>
        <b-col>
          <b-img
            thumbnail
            fluid
            :src="require('../assets/img/home.jpg')"
            alt=""
            width="200"
            height="200"
          ></b-img>
        </b-col>
      </b-row>
    </b-container>
    <vFooter msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import vHeader from "@/components/vHeader.vue";
import vFooter from "@/components/vFooter.vue";

export default {
  name: "Home",
  components: {
    vHeader,
    vFooter,
  },
};
</script>
