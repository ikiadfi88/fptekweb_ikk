<template>
  <NavDash></NavDash>
  <LandingPage></LandingPage>
  <FormPage></FormPage>
  <trackRecord></trackRecord>
  <footerDash></footerDash>
</template>

<script>
import NavDash from "@/components/dashboard/NavDash.vue";
import LandingPage from "@/components/schedule/LandingPage.vue";
import FormPage from "@/components/schedule/FormPage.vue";
import trackRecord from "@/components/home/trackRecord.vue";
import footerDash from "@/components/dashboard/footerDash.vue";

export default {
  name: "ScheduleView",
  components: {
    NavDash,
    LandingPage,
    FormPage,
    trackRecord,
    footerDash,
  },
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@800&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@800&family=Poppins&display=swap");
</style>
