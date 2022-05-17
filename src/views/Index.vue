<template>
  <div class="wrapper">
    <parallax class="page-header header-filter" :style="headerStyle">
      <div class="md-layout">
        <div class="md-layout-item">
          <div class="image-wrapper">
            <div class="brand">
              <h1>Vue Material Kit</h1>
              <h3>A Badass Vue.js UI Kit made with Material Design.</h3>
            </div>
          </div>
        </div>
      </div>
    </parallax>
  </div></template
>

<script>
export default {
  components: {},
  name: "index",
  bodyClass: "index-page",
  props: {},
  data() {
    return {};
  },
  methods: {},
  computed: {},
  mounted() {},
  beforeDestroy() {},
};
</script>

<style lang="scss">
.section-download {
  .md-button + .md-button {
    margin-left: 5px;
  }
}

@media all and (min-width: 991px) {
  .btn-container {
    display: flex;
  }
}
</style>
