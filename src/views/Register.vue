<template>
  <div class="register">
    <mt-header title="会员注册">
      <mt-button icon="back" slot="left"></mt-button>
    </mt-header>
    <div class="form">
      <mt-field label="账号:" placeholder="请输入用户名"></mt-field>
      <mt-field label="密码:" placeholder="请输入密码"></mt-field>
      <mt-field label="确认密码:" placeholder="确认密码"></mt-field>
    </div>
    <mt-button class="btn" size="large">提交注册</mt-button>
    <div class="login"><router-link to="/login">去登陆</router-link></div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.register {
  /* background-color: #ebeced; */
}
.register .mint-header {
  height: 48px;
  font-size: 16px;
  background-color: #84c95b;
}
.register .mint-cell-wrapper {
  background-color: #ebeced;
}
.register .btn {
  background-color: #84c95b;
  color: #fff;
  margin-top: 50px;
}
.register .login {
  text-align: left;
  margin-top: 40px;
}
</style>