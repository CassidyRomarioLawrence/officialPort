<template>
  <div class="home">
    <NavBar />
    <LandingPage />
  </div>
  <div id="about">
    <AboutMe />
  </div>
  <div id="resume">
    <ResumeCom />
  </div>
</template>

<script>
import LandingPage from '@/components/LandingPage.vue';
import NavBar from '@/components/NavBar.vue';
import AboutMe from '@/components/AboutMe.vue';
import ResumeCom from '@/components/ResumeCom.vue';

export default {
  name: 'HomeView',
  components: {
    LandingPage,
    NavBar,
    AboutMe,
    ResumeCom
  }
}
</script>

<style>
.home{
  backdrop-filter: blur(2px);
}
#about{
  background-color: white;
}
</style>
