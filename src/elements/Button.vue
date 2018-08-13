<template>
  <component :is="button" >
        <button class="button">
            <slot>Button</slot>
        </button>
  </component>
</template>

<script>
export default {
  name: "Button",
  status: "ready",
  release: "1.0.0",
}
</script>

<style lang="scss" scoped>
.button {
  background-color: #4caf50; /* Green */
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
}
</style>

<docs>
  ```jsx
  <div>
    <button class="button">The quick brown fox</button>
  </div>
  ```
</docs>
