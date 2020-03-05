<template>
  <footer>
    <div class="container d-flex flex-column align-center footer-content">
      <h1><span class="logo-style">App</span>Lab</h1>
      <nav>
        <ul>
          <li>Home</li>
          <li>Key Features</li>
          <li>Pricing</li>
          <li>Testiminial</li>
          <li>FAQ</li>
        </ul>
      </nav>
      <div class="d-flex icon-padding">
        <div class="icon-padding">
          <IconComponent name="facebook" />
        </div>
        <div class="icon-padding">
          <IconComponent name="twitter" />
        </div>
        <div class="icon-padding">
          <IconComponent name="slack" />
        </div>
        <div class="icon-padding">
          <a href="https://github.com/13KOPADZE/" target="_blank">
            <IconComponent name="github" />
          </a>
        </div>
      </div>
      <p>Copyright© Giorgi Kopadze 2020!. All rights reserved</p>
    </div>
  </footer>
</template>

<script>
import IconComponent from "./IconComponent";
export default {
  components: {
    IconComponent
  }
};
</script>
