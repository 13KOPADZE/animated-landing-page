<template>
  <div class="d-flex flex-column container align-center">
    <div class="text-center reason">
      <h1 data-aos="slide-left" data-aos-duration="10000">
        Why you should choose our app
      </h1>
      <p data-aos="slide-right" data-aos-duration="10000">
        The rise of mobile devices transforms the way we consume information
        entirely and the world's most elevant channels such as Facebook
      </p>
    </div>
    <div
      class="d-flex flex-wrap align-center justify-center"
      data-aos="slide-up"
      data-aos-duration="10000"
    >
      <ReasonCardComponent class="align-center text-center">
        <div class="slot-image-background pink " slot="image">
          <img src="../images/web-design.png" />
        </div>
        <h3 slot="heading">App Development</h3>
      </ReasonCardComponent>
      <ReasonCardComponent class="align-center text-center">
        <div class="slot-image-background light-blue" slot="image">
          <img src="../images/trophy.png" />
        </div>
        <h3 slot="heading">App Development</h3>
      </ReasonCardComponent>
      <ReasonCardComponent class="align-center text-center">
        <div class="slot-image-background light-yellow" slot="image">
          <img src="../images/computer.png" />
        </div>
        <h3 slot="heading">Cloud Storage</h3>
      </ReasonCardComponent>
      <ReasonCardComponent class="align-center text-center">
        <div class="slot-image-background light-green" slot="image">
          <img src="../images/customer-support.png" />
        </div>
        <h3 slot="heading">Customer Support</h3>
      </ReasonCardComponent>
      <ReasonCardComponent class="align-center text-center">
        <div class="slot-image-background light-purple" slot="image">
          <img src="../images/ui-image.png" />
        </div>
        <h3 slot="heading">UX Planing</h3>
      </ReasonCardComponent>
      <ReasonCardComponent class="align-center text-center">
        <div class="slot-image-background light-blue" slot="image">
          <img src="../images/customer-service.png" />
        </div>
        <h3 slot="heading">Customer Support</h3>
      </ReasonCardComponent>
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
