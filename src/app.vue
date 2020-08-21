<template>
	<div id="test">{{text}}</div>
</template>

<script>
	export default {
		data(){
			return {
				text : 'helloWorld'
			}
		}
	}
</script>

<style lang="scss">
	#test{
		color : red;
	}
</style>