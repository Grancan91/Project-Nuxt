<template>
  <div id="container" class="bg-backGround w-screen h-screen flex flex-col justify-center items-center">
    <RebootLogo/>
    <div class="w-fit h-fit bg-backGround">
      <LoginForm/> 
    </div>
  </div>
</template>


<script>
import LoginForm from '@/components/LoginForm.vue'
export default {
  name: 'IndexPage',
  components: {
    LoginForm
  },
}
</script>
