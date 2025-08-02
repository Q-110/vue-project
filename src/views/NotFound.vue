<template>
  <div class="not-found">
    <div class="container">
      <h1 class="title">404</h1>
      <div class="icon">
        <i class="iconfont icon-airplay"></i>
      </div>
      <p class="message">抱歉，您访问的页面飞走了</p>
      <router-link to="/" class="back-btn">返回首页</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: 'NotFound'
}
</script>

<style scoped>
.not-found {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background-color: #f7f9fc;
}

.container {
  text-align: center;
  padding: 40px;
  border-radius: 8px;
  background-color: #fff;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
  max-width: 500px;
  width: 90%;
}

.title {
  font-size: 120px;
  color: #409eff;
  margin: 0;
  line-height: 1.2;
  font-weight: 700;
}

.icon {
  font-size: 80px;
  color: #909399;
  margin: 20px 0;
}

.message {
  font-size: 22px;
  color: #606266;
  margin-bottom: 30px;
}

.back-btn {
  display: inline-block;
  padding: 12px 24px;
  background-color: #409eff;
  color: white;
  text-decoration: none;
  border-radius: 4px;
  font-size: 16px;
  transition: background-color 0.3s;
}

.back-btn:hover {
  background-color: #66b1ff;
}
</style>