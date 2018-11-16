<template>
    <div>
        <div class="header">

        </div>
        <div class="logo-bg">
            <img :src="logoBg" alt="">
        </div>
    </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
import logoBg from '~/assets/avatar.jpg'
export default {
  components: {
    Logo
  },
  data(){
    return {
      logoBg
    }
  },
  mounted(){
    this.logoBg = logoBg
  }
}
</script>

<style>
    
</style>
