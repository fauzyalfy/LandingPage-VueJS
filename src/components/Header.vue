<template>
  <v-app-bar
    app
    color="white"
    light
    elevation="6"
    elevate-on-scroll
    style="padding: 0px 90px"
  >
    <v-toolbar-title> PERIKSAIN </v-toolbar-title>
    <v-spacer />
    <v-list class="d-flex align-center">
      <v-list-item
        link
        v-for="(menu, index) in menus"
        :key="index"
        :to="menu.route"
      >
        <v-list-item-title>{{ menu.title }}</v-list-item-title>
      </v-list-item>
    </v-list>
    <v-btn text>
      <v-icon>mdi-cart</v-icon>
    </v-btn>
    <hr style="border: 0.5px solid black; height: 20px" />
    <v-avatar size="30" style="margin-left: 20px">
      <img src="https://cdn.vuetifyjs.com/images/john.jpg" alt="John" />
    </v-avatar>
    <label style="margin-left: 20px">Hi, Saya</label>
    <v-icon>mdi-chevron-down</v-icon>
  </v-app-bar>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      menus: [
        { title: "Home", route: "home" },
        { title: "OrderLayanan", route: "order" },
        { title: "GabungMitra", route: "gabung" },
        { title: "Artikel", route: "artikel" },
        { title: "Promo", route: "promo" },
        { title: "Bantuan", route: "bantuan" },
      ],
    };
  },
};
</script>
