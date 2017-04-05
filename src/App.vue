<template>
  <div id="app">
		<router-view name='default'></router-view>
	</div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
#app{
  max-width: 650px;
  margin: 0 auto;
  background-color: #EEE;
  min-height: 100vh;
}
</style>
