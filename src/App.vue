<template>
  <div id="app">
		<!-- <img src="./assets/images/logo.png"> -->
		<dl>
			<dt>
				<img src="./assets/images/mark.png" alt="">
			</dt>
			<dd>
				<span>书山有路勤为径，学海无涯苦作舟。</span>
			</dd>
		</dl>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
dl {
	border-bottom: 1px solid #ccc;
}
dl dt img{
	border-radius: 9999px;
}
dl dd {
	height: 100px;
	line-height: 100px;
}
</style>
