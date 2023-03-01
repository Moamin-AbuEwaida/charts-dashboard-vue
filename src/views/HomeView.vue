<template>
  <v-app
    id="home"
    :style="{ background: $vuetify.theme.themes.dark.background }"
  >
    <Sidebar />
    <SidebarRight />
  </v-app>
</template>

<script>
import Sidebar from "@/components/Sidebar.vue";
import SidebarRight from "@/components/SidebarRight.vue";

export default {
  name: "HomeView",

  components: {
    Sidebar,
    SidebarRight,
  },
};
</script>
