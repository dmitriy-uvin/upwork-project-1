<template>
	<div class="flex justify-start items-center lg:w-20p">
		<router-link :to="{ path: '/' }">
			<img src="~/assets/img/logo.png" class="-md:hidden" alt="">
			<img src="~/assets/img/logosmall.png" class="md:hidden" alt="">
		</router-link>
	</div>
</template>

<script>
export default {
	name: "Logo"
}
</script>

<style scoped>

</style>
