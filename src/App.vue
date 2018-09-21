<template>
  <div>
    <CcLogin/>
  </div>
</template>

<script>
import CcLogin from './components/Login'

export default {
  name: 'WebSchoolComponent',
  components: {
    CcLogin
  },

  data () {
    return {
      title: 'Ecommerce Webschool'
    }
  }
}
</script>

<style>

</style>
