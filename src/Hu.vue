<template>
  <div class="hu-container">
    <Editor/>
  </div>
</template>

<script>
  import Editor from "./components/Editor.vue"

  export default {
    props: [],
    components: {
      Editor
    },
    name: 'Hu'
  }

</script>

<style lang="less">
@import './assets/base.less';
html,
body{
  height: 100%;
}
.hu-container{
  position: relative;
  max-width: 568px!important;
  height: 100%;
  min-height: 100%;
  margin: 0 auto;
  background: #2B2B48;
  perspective: 500px;
}
</style>
