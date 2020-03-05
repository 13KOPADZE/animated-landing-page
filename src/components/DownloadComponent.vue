<template>
  <div class="padding download-background">
    <div class="container">
      <div class="download">
        <h1>Download our App now !</h1>
        <p>
          The rise of mobile devices transforms the way we consume information
          entirely and the world's most elevant channels such as Facebook.
        </p>
        <div class="d-flex download-source">
          <div class="download-links">
            <IconComponent name="google-play" />
          </div>
          <div class="download-links">
            <IconComponent name="app-store" />
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
