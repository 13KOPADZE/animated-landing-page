<template>
  <div class="container d-flex reasons justify-around padding">
    <div>
      <div class="ultimate-feature">
        <h1>Ultimate features that we build</h1>
        <p>
          The rise of mobile devices transforms the way we consume information
          entirely
        </p>
      </div>
      <div class="d-flex flex-wrap">
        <ReasonCardComponent>
          <div class="slot-image-background pink" slot="image">
            <img src="../images/web-design.png" />
          </div>
          <h3 slot="heading">App Development</h3>
        </ReasonCardComponent>
        <ReasonCardComponent>
          <div class="slot-image-background light-green" slot="image">
            <img src="../images/ui-image.png" />
          </div>
          <h3 slot="heading">UX Planing</h3>
        </ReasonCardComponent>
        <ReasonCardComponent>
          <div class="slot-image-background light-yellow" slot="image">
            <img src="../images/computer.png" />
          </div>
          <h3 slot="heading">Cloud Storage</h3>
        </ReasonCardComponent>
        <ReasonCardComponent>
          <div class="slot-image-background light-blue" slot="image">
            <img src="../images/customer-service.png" />
          </div>
          <h3 slot="heading">Customer Support</h3>
        </ReasonCardComponent>
        <button class="button">See all</button>
      </div>
    </div>
    <div class="relative">
      <div class="mobile-form">
        <img src="../images/mobile-form.png" />
      </div>
      <div class="mobile-form-2">
        <img src="../images/mobile-form-2.png" />
      </div>
    </div>
  </div>
</template>
<script>
import ReasonCardComponent from "./ReasonCardComponent";
export default {
  components: {
    ReasonCardComponent
  }
};
</script>
