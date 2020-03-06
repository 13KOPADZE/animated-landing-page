<template>
  <div id="app">
    <HeaderComponent />
    <HeroComponent />
    <TrustedCompaniesComponent />
    <AppFeatureComponent />
    <JackpotComponent />
    <DesignComponent />
    <ReasonComponent />
    <UltimateFeatureComponent />
    <ChargesComponent />
    <RateComponent />
    <FAQComponent />
    <DownloadComponent />
    <FooterComponent />
  </div>
</template>

<script>
import HeaderComponent from "./components/HeaderComponent";
import HeroComponent from "./components/HeroComponent";
import TrustedCompaniesComponent from "./components/TrustedCompaniesComponent";
import AppFeatureComponent from "./components/AppFeatureComponent";
import JackpotComponent from "./components/JackpotComponent";
import DesignComponent from "./components/DesignComponent";
import ReasonComponent from "./components/ReasonComponent";
import UltimateFeatureComponent from "./components/UltimateFeatureComponent";
import ChargesComponent from "./components/ChargesComponent";
import RateComponent from "./components/RateComponent";
import FAQComponent from "./components/FAQComponent";
import DownloadComponent from "./components/DownloadComponent";
import FooterComponent from "./components/FooterComponent";
import AOS from "aos";
import "aos/dist/aos.css";

AOS.init({
  // Settings that can be overridden on per-element basis, by `data-aos-*` attributes:
  offset: 100, // offset (in px) from the original trigger point
  delay: 200, // values from 0  to 3000, with step 50ms
  duration: 800, // values from 0 to 3000, with step 50ms
  anchorPlacement: "top-bottom" // defines which position of the element regarding to window should trigger the animation
});

export default {
  name: "App",
  components: {
    HeaderComponent,
    HeroComponent,
    TrustedCompaniesComponent,
    AppFeatureComponent,
    JackpotComponent,
    DesignComponent,
    ReasonComponent,
    UltimateFeatureComponent,
    ChargesComponent,
    RateComponent,
    FAQComponent,
    DownloadComponent,
    FooterComponent
  }
};
</script>
<style>
@import url("style/style.css");
</style>
