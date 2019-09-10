<template>
  <svg class="icon">
    <use :xlink:href="`#icon-${icon}`" />
  </svg>
</template>

<script>
export default {
  props: {
    icon: {
      type: String,
      default: ""
    }
  }
};
</script>

<style>
svg {
  max-height: 1em;
  max-width: 1em;
  color: inherit;
  fill: currentcolor;
}
</style>