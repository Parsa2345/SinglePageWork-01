<template>
  <!-- <p></p> -->
<Preloader />
<HeaderTop />
<OilHeader />
<OilBanner />
<FeaturesArea />
<AboutArea />
<ServicesArea />
<WhyChooseUsArea />
<PartnerArea />
<OverflowHiddenBox />
<ProjectsArea />
<OilBlog />
<OilFooter />

  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <!-- <Footer /> -->
</template>

<script>
import Preloader from './components/Preloader.vue';
import HeaderTop from './components/HeaderTop.vue';
import OilHeader from './components/OilHeader.vue';
import OilBanner from './components/OilBanner.vue';
import FeaturesArea from './components/FeaturesArea.vue';
import AboutArea from './components/AboutArea.vue';
import ServicesArea from './components/ServicesArea.vue';
import WhyChooseUsArea from './components/WhyChooseUsArea.vue';
import PartnerArea from './components/PartnerArea.vue';
import OverflowHiddenBox from './components/OverflowHiddenBox.vue';
import ProjectsArea from './components/ProjectsArea.vue';
import OilBlog from './components/OilBlog.vue';
import OilFooter from './components/OilFooter.vue'; 

export default {
  name: 'App',
  components: {
    Preloader,
    HeaderTop,
    OilHeader,  
    OilBanner,
    FeaturesArea,
    AboutArea,
    ServicesArea,
    OilBlog,
    WhyChooseUsArea,
    PartnerArea,
    OverflowHiddenBox,
    ProjectsArea,
    OilFooter,
  }
}
</script>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
