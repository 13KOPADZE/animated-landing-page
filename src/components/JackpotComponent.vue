<template>
  <div class="container jackpot">
    <div class="d-flex jackpot-content">
      <div class="jackpot-heading">
        <h1>Smart jackpots that you may love this anytime & anywhere</h1>
      </div>
      <div class="jackpot-text">
        <p>
          The rise of mobile devices transforms the way we consume information
          entirely and the world's most elevant channels such as Facebook
        </p>
      </div>
    </div>
    <div class="jackpot-list d-flex">
      <div class="jackpot-info">
        <div class="icon-background icon-padding">
          <IconComponent name="bill" />
        </div>
        <div>
          <h2 class="red">
            Automatic Payouts
          </h2>
          <p>
            Get your blood tests delivered at home collect a sample from the
            news your blood tests.
          </p>
        </div>
      </div>
      <div class="jackpot-info">
        <div class="icon-background icon-padding">
          <IconComponent name="network" />
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
      <div class="jackpot-info">
        <div class="icon-background icon-padding">
          <IconComponent name="badge" />
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
</template>

<script>
import IconComponent from "./IconComponent";

export default {
  components: {
    IconComponent
  }
};
</script>
