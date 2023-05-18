<template>
<h1>欢迎来到仓库进销存系统</h1>
</template>
<script>
export default {
  name: "Index",
  data() {
    return {
      // 版本号
      version: "3.8.4",
    };
  },
  methods: {
    goTarget(href) {
      window.open(href, "_blank");
    },
  },
};
</script>
<style>
h1{

}
</style>