<template>
  <template>
    <h1>这是找回密码页</h1>
    <h2 @click="goLogin">登录页</h2>
    <h2 @click="goIndex">首页</h2>
    <h2 @click="goRegister">注册</h2>
  </template>
</template>
<script>
    export default{
        name: "findPasw",
        data(){
            return {}
        },
        methods: {
          goLogin () {
            location.assign('login.html')
          },
          goIndex(){
            location.assign('index.html')
          },
          goRegister(){
            location.assign('register.html')
          }
        }
    }
</script>
<style>

</style>
