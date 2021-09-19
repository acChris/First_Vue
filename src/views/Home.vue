<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <Login msg="Welcome to Your Login Component" />
    <Admin msg="Welcome to Your Admin Component"/>
  
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Login from '../components/Login.vue'
import Admin from '../components/Admin.vue'

export default {
  name: 'Home',
  data(){
    return {
      msg: "Welcome to Your Vue.js App"
    }
  },
  components: {
    HelloWorld,
    Login,
    Admin
  }
}
</script>
