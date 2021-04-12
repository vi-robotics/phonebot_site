<template>
  <v-app>
    <v-app-bar app color="primary" dark>
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="@/assets/phonebot_logo/phonebot_logo.svg"
          transition="scale-transition"
          width="40"
        />
        <h1>PhoneBot</h1>
      </div>

      <v-spacer></v-spacer>

      <v-btn
        href="https://github.com/vi-robotics/phonebot_docs"
        target="_blank"
        text
      >
        <span class="mr-2">Docs</span>
        <v-icon>mdi-open-in-new</v-icon>
      </v-btn>
    </v-app-bar>

    <v-main>
      <SplashPage />
    </v-main>
  </v-app>
</template>

<script>
import SplashPage from "./components/SplashPage";

export default {
  name: "App",

  components: {
    SplashPage,
  },

  data: () => ({
    //
  }),
};
</script>
