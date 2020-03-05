<template>
  <header>
    <h1><span class="logo-style">App</span>Lab</h1>
    <nav class="nav-bar">
      <ul>
        <li>Home</li>
        <li>Key Features</li>
        <li>Pricing</li>
        <li>Testiminial</li>
        <li>FAQ</li>
        <li><button class="button">Try for free</button></li>
      </ul>
    </nav>
    <nav
      class="mobile-nav"
      v-if="isActive"
      v-bind:class="{ navActive: isActive }"
    >
      <ul>
        <li>Home</li>
        <li>Key Features</li>
        <li>Pricing</li>
        <li>Testiminial</li>
        <li>FAQ</li>
        <li><button class="button">Try for free</button></li>
      </ul>
    </nav>
    <div class="mobile-nav-toggler" @click="toggleNav()">
      <div class="bar1"></div>
      <div class="bar2"></div>
      <div class="bar3"></div>
    </div>
  </header>
</template>
<script>
export default {
  data() {
    return {
      isActive: false
    };
  },
  methods: {
    toggleNav() {
      this.isActive = !this.isActive;
    }
  }
};
</script>
