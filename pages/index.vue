<template>
  <div>
    <!-- -----------------------------------------------
    All Components
    ----------------------------------------------- -->
    <AllCustomComponents />
    <!-- 
    <ComingSoon />
-->
  </div>
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
          content: "Follou.Co",
        },
      ],
    };
  },

  data() {
    return {};
  },
  components: {
    Banner: () => import("@/components/shared/lp-banner/Banner"),
    ComingSoon: () => import("@/components/shared/coming-soon/ComingSoon"),
    AllCustomComponents: () =>
      import("@/components/custom/AllCustomComponents"),
  },
};
</script>
