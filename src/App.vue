<template>
  <div id="app">
    <HeaderComponent />
    <HeroComponent />
    <TrustedCompaniesComponent />
    <AppFeatureComponent />
    <JackpotComponent />
    <DesignComponent />
    <ReasonsComponent />
  </div>
</template>

<script>
import HeaderComponent from "./components/HeaderComponent";
import HeroComponent from "./components/HeroComponent";
import TrustedCompaniesComponent from "./components/TrustedCompaniesComponent";
import AppFeatureComponent from "./components/AppFeatureComponent";
import JackpotComponent from "./components/JackpotComponent";
import DesignComponent from "./components/DesignComponent";
import ReasonsComponent from "./components/ReasonsComponent";

export default {
  name: "App",
  components: {
    HeaderComponent,
    HeroComponent,
    TrustedCompaniesComponent,
    AppFeatureComponent,
    JackpotComponent,
    DesignComponent,
    ReasonsComponent
  }
};
</script>
<style>
@import url("style/style.css");
</style>
