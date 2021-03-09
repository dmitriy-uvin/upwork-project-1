<template>
	<nav
		id="nav"
		class="flex -lg:flex-wrap font-SourceSansPro relative z-50
			 justify-between items-center h-16 -lg:pt-2 shadow lg:px-8 -lg:px-4 text-black"
	>
		<Logo />
		<Links />
		<HeaderButtons />
	</nav>
</template>

<script>
import headerMixin from "@/mixins/headerMixin";
import Logo from "@/components/layout/header/Logo";
import Links from "@/components/layout/header/Links";
import HeaderButtons from "@/components/layout/header/HeaderButtons";
export default {
	name: "Header",
	mixins: [headerMixin],
	components: {
		Logo, Links, HeaderButtons
	}
}
</script>

<style scoped>

</style>
