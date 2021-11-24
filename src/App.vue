<template>
  <v-app>
    <Header />
    <v-main>
      <Content />
    </v-main>
  </v-app>
</template>

<script>
import Header from "./components/Header.vue";
import Content from "./components/Content.vue";

export default {
  name: "App",
  components: { Header, Content },
};
</script>
