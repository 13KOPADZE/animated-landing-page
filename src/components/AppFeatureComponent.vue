<template>
  <div class="app-feature-section container">
    <img src="../images/feature-app-image.png" />
    <div class="feature-content">
      <div>
        <h1>Awsome apps features</h1>
        <p>
          Increase productivity with a simple to-do app. app for managing your
          personal budgets.
        </p>
      </div>
      <div class="feature-list">
        <div class="feature-info">
          <div class="icon-background icon-padding">
            <IconComponent name="speed" />
          </div>
          <div>
            <h2 class="red">
              Fast Performance
            </h2>
            <p>
              Get your blood tests delivered at home collect a sample from the
              news your blood tests.
            </p>
          </div>
        </div>
        <div class="feature-info">
          <div class="icon-background icon-padding">
            <IconComponent name="prototyping" />
          </div>
          <div>
            <h2 class="blue">
              Prototyping
            </h2>
            <p>
              Get your blood tests delivered at home collect a sample from the
              news your blood tests.
            </p>
          </div>
        </div>
        <div class="feature-info">
          <div class="icon-background icon-padding">
            <IconComponent name="pen" />
          </div>
          <div>
            <h2 class="green">
              Vector Editing
            </h2>
            <p>
              Get your blood tests delivered at home collect a sample from the
              news your blood tests.
            </p>
          </div>
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
