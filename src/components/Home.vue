<template>
  <div>
    <Homeview/>
    <br>
    <AboutMe/>
    <br>
    <br>
    <BasicSkills/>
    <br>
    <MyPortfolio/>
    <br>
    <!-- <Contacts/> -->
  </div>
</template>


<style scoped>

</style>

<script>
import Homeview from "@/components/home_view/Homeview"
import AboutMe from "@/components/home_view/AboutME";
import BasicSkills from "@/components/home_view/BasicSkills";
import MyPortfolio from "@/components/home_view/MyPortfolio";
// import Contacts from "@/components/home_view/Contact";

export default {
  components: {
    Homeview,
    AboutMe,
    BasicSkills,
    // Contacts,
    MyPortfolio
  },
  data() {
    return {
      tab: null,
        text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.',
    };
  }
};
</script>
