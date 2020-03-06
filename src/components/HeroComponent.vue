<template>
  <div class="hero-section">
    <div class="background">
      <div class="hero-content container">
        <div
          class="hero-content-info"
          data-aos="slide-right"
          data-aos-duration="10000"
        >
          <div class="editors-choice">
            <div class="icon-style">
              <IconComponent name="checked" />
            </div>
            <p>#1 Editors Choice App of 2020</p>
          </div>
          <h1>Best app for your modern lifestyle</h1>
          <p>
            Increase productivity with a simple to-do app. app for managing your
            personal budgets.
          </p>
          <div class="demo-section">
            <button>Try for free</button>
            <p>Watch demo video</p>
          </div>
        </div>
        <div data-aos="slide-left" data-aos-duration="10000">
          <img src="../images/app-image.png" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import IconComponent from "./IconComponent";
export default {
  components: {
    IconComponent
  }
};
</script>
