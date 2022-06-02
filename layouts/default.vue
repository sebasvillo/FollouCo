<template>
  <v-app dark>
    <!--v-if="$route.name!=='login'"-->
    <v-main>
      <nuxt />
    </v-main>
    <Footer />
  </v-app>
</template>

<script>
export default {
  head() {
    return {
      title: "Follou.Co",
      meta: [
        {
          hid: "description",
          name: "Follou.Co",
          content: "Follou.Co"
        }
      ]
    };
  },
  components: {
    Header: () => import("@/layouts/sections/Header"),
    Footer: () => import("@/layouts/sections/Footer")
  },
  methods: {}
};
</script>

<style></style>
