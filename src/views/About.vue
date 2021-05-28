<!--
 * @Descripttion:
 * @version:
 * @Author: 雒小霞
 * @Date: 2021-05-28 08:42:02
 * @LastEditors: 雒小霞
 * @LastEditTime: 2021-05-28 10:16:55
-->
<template>
  <div class="about">
    <h1>This is an about page</h1>
    <h1>This is an about page -lxx</h1>
    <h1>This is an about page -lxx</h1>
    <h1>This is an about page -lxx</h1>
    <h1>This is an about page -lxx</h1>
    <h1>This is an about page -lxx</h1>
    <h1>This is an about page -lxx</h1>
    <h1>This is an about page -lxx</h1>

  </div>
</template>
<script>
export default {
  /**
   * 就是想来一点冲突，
   */
  name: "About",
  methods: {
    xxx() {
      // 不知名函数
      console.log("不知道该写点啥");
    },
  },
};
</script>
<style lang="scss" scoped>
div{
  border: 1px solid #eee;
  h1 {
    text-align: center;
    color: red;
    display: inline;
  }
}
