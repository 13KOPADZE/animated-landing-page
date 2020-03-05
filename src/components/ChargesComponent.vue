<template>
  <div class="margin">
    <div class="container align-center d-flex flex-column">
      <div class="charges-headings">
        <h1>Get awesome features, without extra charges</h1>
        <p>
          The rise of mobile devices transforms the way we consume information
          entirely and the world's most elevant channels such as Facebook
        </p>
      </div>
      <div class="option d-flex flex-column align-center">
        <span class="switcher switcher-1">
          <input type="checkbox" id="switcher-1" />
          <label for="switcher-1"></label>
        </span>
      </div>
      <div class="d-flex justify-between padding charges-component">
        <ChargesCardComponent>
          <div slot="charges-info">
            <div class="charges-info-heading">
              <h1>$0</h1>
              <p>/ month</p>
            </div>
            <h2>Business Class</h2>
            <p>For small teams or office</p>
          </div>
          <button slot="button">Start free trail</button>
        </ChargesCardComponent>
        <ChargesCardComponent>
          <div slot="charges-info">
            <div class="charges-info-heading">
              <h1>$99</h1>
              <p>/ month</p>
            </div>
            <h2>Pro Master</h2>
            <p>For Best opportunities</p>
          </div>
          <button slot="button">Subscribe Now</button>
          <p class="free-trail" slot="add-info">Or start 14 days trail</p>
        </ChargesCardComponent>
      </div>
    </div>
  </div>
</template>

<script>
import ChargesCardComponent from "./ChargesCardComponent";

export default {
  components: {
    ChargesCardComponent
  }
};
</script>
