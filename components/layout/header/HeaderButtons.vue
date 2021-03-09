<template>
	<ul class="flex justify-end items-center lg:space-x-4 lg:w-20p">
		<img src="~/assets/img/svg/search.svg" alt="">
		<img src="~/assets/img/svg/menu-burger.svg" alt="" @click="toggleMenu">
	</ul>
</template>

<script>
import headerMixin from "@/mixins/headerMixin";
export default {
	name: "HeaderButtons",
	mixins: [headerMixin]
}
</script>

<style scoped>

</style>
