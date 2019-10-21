<template>
  <button class="v-button">按钮</button>
</template>

<script>
	export default {
		name: "button"
	}
</script>

<style  lang="scss">
  .v-button {
    font-size: var(--font-size);
    height: var(--button-height);
    padding: 0 1em;
    border-radius: var(--border-radius);
    border: 1px solid var(--border-color);
    background: var(--button-bg);
    &:hover {
      background-color: var(--border-color-hover);
    }
    &:active {
      background-color: var(--button-active-bg);
    }
    &:focus {
      outline: none;
    }
  }
</style>
