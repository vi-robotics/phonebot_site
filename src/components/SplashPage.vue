<template>
  <v-container>
    <v-row class="align-center">
      <v-col cols="12">
        <v-row class="pa-6" align="center"
          ><v-img
            :src="require('../assets/phonebot_demo.gif')"
            contain
            height="500"
        /></v-row>
      </v-col>
    </v-row>
    <v-row justify="center" class="text-center">
      <v-col cols="8" class="mb-4">
        <h1 class="display-2 font-weight-bold mb-3">Robotic Phone Case</h1>

        <p class="subheading font-weight-regular">
          PhoneBot is an Open Source robotic phone case which gives your phone
          legs! PhoneBot is small, cheap, won't hurt you and is super easy to
          use. All you need is the
          <a
            href="https://github.com/vi-robotics/phonebot_flutter"
            target="_blank"
            >PhoneBot App</a
          >
          (which works in IOS and Android) and a PhoneBot and you'll be able to
          control and program your robot!
        </p>
        <p class="subheading font-weight-regular">
          Although PhoneBot is easy to use, it is not just a toy. It is a
          research-grade robot designed to be used to develop state-of-the-art
          algorithms combining the mobile processing power of modern smart
          phones with a flexible and robust physical platform.
        </p>
        <h2 class="subheading font-weight-regular">
          <b>Ready to get started?</b>
        </h2>
      </v-col>
    </v-row>
    <v-row justify="center">
      <v-col class="mb-5" cols="3">
        <v-card href="https://github.com/vi-robotics/phonebot_docs">
          <v-row justify="center">
            <v-icon size="200">mdi-hammer-wrench</v-icon>
          </v-row>
          <v-row justify="center" class="pa-5">
            <h3>Build From Scratch</h3>
          </v-row>
        </v-card>
      </v-col>
      <v-col class="mb-5" cols="3">
        <v-card disabled>
          <v-row justify="center">
            <v-icon size="200">mdi-package-variant-closed</v-icon>
          </v-row>
          <v-row justify="center" class="pa-5">
            <h3>Get a Kit</h3>
          </v-row>
        </v-card>
      </v-col>
      <v-col class="mb-5" cols="3">
        <v-card disabled>
          <v-row justify="center">
            <v-icon size="200">mdi-currency-usd</v-icon>
          </v-row>
          <v-row justify="center" class="pa-5">
            <h3>Buy a PhoneBot</h3>
          </v-row>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "SplashPage",
};
</script>
