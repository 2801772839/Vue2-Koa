<template>
  <div class="footer">
    <div style="border-top: 1px #1f1f1f solid">
      <p class="alt" style="color: #999; line-height: 0">
        &copy; 版权所有：Anysg &nbsp;
        <span>技术支持：</span>
        <a href="" target="_blank" style="color: #999">Anysg & LDS</a>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Footer',
}
</script>

<style scoped>
* {
  margin: 0;
  padding: 0;
  font-family: '微软雅黑', Arial, Helvetica, sans-serif;
}

body {
  font-size: 15px;
}

div {
  font-size: 15px;
}

span {
  font-size: 15px;
}

.footer {
  background: #2b2e33;
}

.footer .alt {
  overflow: hidden;
  padding: 20px 0;
  width: 1160px;
  margin: auto;
  text-align: center;
}

.footer .alt .foot {
  width: 138px;
  float: left;
}
.footer .alt .foot p {
  color: #fff;
  line-height: 28px;
}

a {
  text-decoration: none;
}

.footer .alt .foot a {
  color: #999;
  display: block;
  line-height: 24px;
}
</style>
