<template>
	<div>
		我是About
	</div>
</template>

<script>
	export default {
		name:"About",
		// created(){
		// 	document.title="关于"
		// }
		created(){
			console.log("About created")
		},
		destroyed(){
			console.log("About destroyed")
		}
	}
</script>

<style scoped>
</style>
