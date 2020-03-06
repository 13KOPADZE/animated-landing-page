<template>
  <footer>
    <div class="container d-flex flex-column align-center footer-content">
      <h1 data-aos="slide-left" data-aos-duration="10000">
        <span class="logo-style">App</span>Lab
      </h1>
      <nav data-aos="slide-right" data-aos-duration="10000">
        <ul>
          <li>Home</li>
          <li>Key Features</li>
          <li>Pricing</li>
          <li>Testiminial</li>
          <li>FAQ</li>
        </ul>
      </nav>
      <div
        class="d-flex icon-padding"
        data-aos="slide-left"
        data-aos-duration="10000"
      >
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
      <p data-aos="slide-right" data-aos-duration="10000">
        Copyright© Giorgi Kopadze 2020!. All rights reserved
      </p>
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
