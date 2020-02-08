<template>
  <div class="logo-wrapper">
    <div
      :class="{
        'logo-inner': true
      }"
    >
      <img
        :src="`/logo.jpg`"
      />
    </div>
  </div>
</template>
<script>
export default {
  name: 'SiteLogo',
  data() {
    return {
      currentFrame: 1
    }
  }
}
</script>
<style lang="scss">
.logo-wrapper {
  position: relative;
  height: 7s0px;
  overflow: hidden;
  width: 250px;
  .logo-inner {
    position: absolute;
    height: 500px;
    img {
      display: block;
      height: 40px;
      margin: 5px;
      max-height: initial;
    }
  }
}
</style>
