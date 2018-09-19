<template>
  <div>
    <h1>Olá mundo!!</h1>
    <CcIntro></CcIntro>
  </div>
</template>

<script>
import CcIntro from './Intro.vue'

export default {
  components: {
    CcIntro
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  h1, h2 {
    font-weight: normal;
    color: red;
  }
</style>
