<template>
  <div>
    <h1>这是首页</h1>
    <h2 @click="goLogin">登录页</h2>
    <h2 @click="goRegister">注册</h2>
    <h2 @click="gofindPasw">找回密码</h2>
  </div>


</template>

<script>
  export default {
    name: 'index',
    methods: {
      goLogin () {
        location.assign('login.html')
      },
      goRegister(){
        location.assign('register.html')
      },
      gofindPasw(){
        location.assign('findPasw.html')
      }
    },
    beforeCreate(){

      /* 权限控制
      *  查找sessionStorage 是否有 userInfo
      *  no:跳到登录页
      *  yes:渲染首页
      * */
    },

    created(){

    }
  }
</script>


<style>

</style>
