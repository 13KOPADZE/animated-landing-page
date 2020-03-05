<template>
  <div class="accordion-padding" @click="toggle">
    <button class="accordion">
      <div class="d-flex align-center inline">
        <slot name="accordion-heading" />
      </div>
    </button>
    <div class="panel" :class="{ show: isVisable, active: isVisable }">
      <slot name="accordion-text"> </slot>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      isVisable: false
    };
  },
  methods: {
    toggle() {
      this.isVisable = !this.isVisable;
    }
  }
};
</script>
