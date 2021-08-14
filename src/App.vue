<template>
  <v-app>
    <v-container>
      <NavBar />
      <v-container>
        <router-view />
      </v-container>
    </v-container>
  </v-app>
</template>

<script>
import NavBar from "@/components/NavBar";
export default {
  name: "App",
  components: {
    NavBar,
  },
};
</script>
