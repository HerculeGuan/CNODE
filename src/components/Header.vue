<template>
  <div class="header">
    <router-link :to="{name:'root'}">
      <img src="../assets/cnodejs_light.svg" alt>
    </router-link>
    <ul>
      <li>
        <router-link :to="{name:'root'}">
          <a href="#">首页</a>
        </router-link>
      </li>
      <li>
        <a href="#">新手入门</a>
      </li>
      <li>
        <a href="#">API</a>
      </li>
      <li>
        <a href="#">关于</a>
      </li>
      <li>
        <a href="#">注册</a>
      </li>
      <li>
        <a href="#">登陆</a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style scoped>
.header {
  background-color: #444444;
  height: 50px;
}

img {
  max-width: 120px;
  margin-left: 70px;
  margin-top: 10px;
}
ul {
  list-style: none;
  float: right;
  margin: 4px;
  margin-right: 50px;
}
li {
  display: inline-block;
  padding: 10px 15px;
}
a {
  text-decoration: none;
  color: #ccc;
  font-size: 14px;
}
</style>