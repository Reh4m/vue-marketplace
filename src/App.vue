<template>
  <v-app>
    <AppBar />

    <v-main>
      <BottomNav />

      <router-view />
    </v-main>
  </v-app>
</template>

<script>
import AppBar from "@/components/AppBar.vue";
import BottomNav from "@/components/BottomNav.vue";

export default {
  name: "App",
  components: {
    AppBar,
    BottomNav,
  },
};
</script>
