<template>
  <div class="home">
    <app-navbar />
    <app-header />
    <app-start-earning />
    <app-perks />
    <app-one-click-away />
  </div>
</template>

<script>
// @ is an alias to /src
import appNavbar from "@/components/Navbar.vue";
import appHeader from "@/components/Header.vue";
import appStartEarning from "@/components/StartEarning.vue";
import appPerks from "@/components/Perks.vue";
import appOneClickAway from "@/components/OneClickAway.vue";

export default {
  name: "Home",
  components: {
    appNavbar,
    appHeader,
    appStartEarning,
    appPerks,
    appOneClickAway
  }
};
</script>
