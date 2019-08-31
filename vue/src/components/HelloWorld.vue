<template>
  <div class="hello">
    {{count}}<button @click="add()">+</button><button @click="down()">-</button>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
      count : 0
    }
  },
  methods : {
    add : function() {
      this.count++;
    },
    down : function() {
      this.count--;
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
