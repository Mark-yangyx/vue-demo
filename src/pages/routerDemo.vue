<template lang="pug">
  div
    span {{msg}}
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your router App'
    }
  }
}
</script>
