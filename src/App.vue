<template>
  <v-app class="container">
    <v-main class="container">
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
export default {
  name: "App",

  data: () => ({
    //
  }),
};
</script>
<style lang="scss" scoped>
.container {
  background: #e5e5e5;
  height: 100%;
}
</style>
