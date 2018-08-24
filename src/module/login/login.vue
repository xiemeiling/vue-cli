<template>
  <div>
    <h1 >这是登录页</h1>
    <h2 @click="goIndex">首页</h2>
    <h2 @click="goRegister">注册</h2>
    <h2 @click="gofindPasw">找回密码</h2>
  </div>

</template>

<script>
  export default {
    name: 'login',
    methods: {
      goRegister () {
        location.assign('register.html')
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
