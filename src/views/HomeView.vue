<template>
  <!-- <HelloWorld /> -->
  <HeaderComponents/>
</template>

<script>
import { defineComponent } from "vue";

// Components
// import HelloWorld from "../components/HelloWorld.vue";
import HeaderComponents from "@/components/public/HeaderComponents.vue";
export default defineComponent({
  name: "HomeView",
  components: {
    HeaderComponents,
  },
});
</script>
