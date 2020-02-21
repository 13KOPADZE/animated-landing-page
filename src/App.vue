<template>
  <div id="app">
    <HeaderComponent />
    <HeroComponent />
    <TrustedCompaniesComponent />
    <AppFeatureComponent />
  </div>
</template>

<script>
import HeaderComponent from "./components/HeaderComponent";
import HeroComponent from "./components/HeroComponent";
import TrustedCompaniesComponent from "./components/TrustedCompaniesComponent";
import AppFeatureComponent from "./components/AppFeatureComponent";

export default {
  name: "App",
  components: {
    HeaderComponent,
    HeroComponent,
    TrustedCompaniesComponent,
    AppFeatureComponent
  }
};
</script>
<style>
@import url("style/style.css");
</style>
