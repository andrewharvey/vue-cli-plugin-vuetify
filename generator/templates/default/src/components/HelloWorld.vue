<template>
  <blockquote>
    &#8220;{{ msg }}&#8221;
    <footer>
      <small>
        <em>&mdash;{{ author }}</em>
      </small>
    </footer>
  </blockquote>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data () {
    return {
      author: 'John Johnson'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
// TODO add some styles
</style>
