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
AOS.init();

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
