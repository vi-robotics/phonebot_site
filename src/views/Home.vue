<template>
  <div class="home">
    <img alt="PhoneBot logo" src="../assets/phonebot_logo/phonebot_logo.svg" />
    <SplashPage />
  </div>
</template>

<script>
// @ is an alias to /src
import SplashPage from "@/components/SplashPage.vue";

export default {
  name: "Home",
  components: {
    SplashPage,
  },
};
</script>
