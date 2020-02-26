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
    UltimateFeatureComponent
  }
};
</script>
<style>
@import url("style/style.css");
</style>
