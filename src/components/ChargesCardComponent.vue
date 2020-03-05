<template>
  <div class="pad">
    <div class="d-flex flex-column align-center text-center charges-align">
      <div class="charges-info">
        <slot name="charges-info" />
      </div>
      <div class="charges-details">
        <p>Drag & Drop Builder</p>
        <p>1,000's of Templates</p>
        <p>Blog Support Tools</p>
        <p>eCommerce Store</p>
      </div>
      <slot class="button" name="button" />
      <slot name="add-info" />
    </div>
  </div>
</template>
