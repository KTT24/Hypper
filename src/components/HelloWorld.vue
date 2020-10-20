<template>
  <h1></h1>
</template>

<script>
export default {
  beforeMount() {
      this.delay(5000);
  },

  name: 'HelloWorld',
  props: {
    msg: String
  },
  methods: {
    delay(ms) {
      const startPoint = new Date().getTime();
      while (new Date().getTime() - startPoint <= ms) {
        /* wait */
      }
    }
  }
}



</script>



<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
