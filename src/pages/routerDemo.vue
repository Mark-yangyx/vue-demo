<template lang="pug">
div.demo-wrapper
	span {{msg}}
	span.title 以下为技术链接记录：
	a(href="https://blog.csdn.net/u013778905/article/details/83501204") 关于github设置ssh
	a(href="https://www.jianshu.com/p/c02f5f94b77e") 关于在vue里面使用stylus
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

<style lang="stylus" scoped>
	@import './demo.styl';
</style>
