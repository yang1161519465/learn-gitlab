<!--
 * @Descripttion: 
 * @version: 
 * @Author: 雒小霞
 * @Date: 2021-05-28 08:42:02
 * @LastEditors: 杨旭晨
 * @LastEditTime: 2021-05-28 09:11:35
-->
<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <!-- 添加了一个新功能 -->
    <div class="container">
      <div class="left">一些标题</div>
      <div class="right">
        <ul>
          <li>1</li>
          <li>2</li>
          <li>3</li>
          <li>4</li>
          <li>5</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    // HelloWorld,
  },
};
</script>
