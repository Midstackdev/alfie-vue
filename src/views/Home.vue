<template>
  <div class="home">
    <BaseHeader v-if="shouldShowHomeNav" />
    <OtherHeader v-else />
    <router-view></router-view>
    <BaseFooter />
  </div>
</template>

<script>
// @ is an alias to /src
import BaseHeader from "@/components/BaseHeader.vue";
import OtherHeader from "@/components/OtherHeader.vue";
import BaseFooter from "@/components/BaseFooter.vue";

export default {
  name: "Home",
  components: {
    BaseHeader,
    BaseFooter,
    OtherHeader,
  },
  computed: {
    shouldShowHomeNav() {
      const routes = ["/"];
      return routes.includes(this.$route.path);
    },
  },
};
</script>
