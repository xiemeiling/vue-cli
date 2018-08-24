<template>
  <div>
    <h1>这是注册页</h1>
    <h2 @click="goLogin">登录页</h2>
    <h2 @click="goIndex">首页</h2>
    <h2 @click="gofindPasw">找回密码</h2>
  </div>

</template>

<script>
  export default {
    name: 'register',
    methods: {
      goLogin () {
        location.assign('login.html')
      },
      goIndex(){
        location.assign('index.html')
      },
      gofindPasw(){
        location.assign('findPasw.html')
      }
    }
  }
</script>
<style>

</style>
