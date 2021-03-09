<template>
	<ul ref="menu"
		class="flex -lg:flex-col lg:justify-center lg:items-center lg:space-x-4 lg:w-80p -lg:order-3 -lg:w-full -lg:bg-black -lg:text-white -lg:py-1 -lg:mt-4"
		:class="{ '-lg:hidden': !menuToggled }"
	>
		<li>
			<router-link :to="{ name: 'photo' }" class="-lg:px-4 -lg:py-1 -lg:hover:bg-red cursor-pointer">
				Artikelen
			</router-link>
		</li>
		<li>
			<router-link :to="{ name: 'video' }" class="-lg:px-4 -lg:py-1 -lg:hover:bg-red cursor-pointer">
				Video’s
			</router-link>
		</li>
		<li>
			<router-link :to="{ name: 'subjects' }" class="-lg:px-4 -lg:py-1 -lg:hover:bg-red cursor-pointer">
				Onderwerpen
			</router-link>
		</li>
		<li>
			<router-link :to="{ name: 'sermons' }" class="-lg:px-4 -lg:py-1 -lg:hover:bg-red cursor-pointer">
				Preken
			</router-link>
		</li>
		<li>
			<router-link :to="{ name: 'podcasts' }" class="-lg:px-4 -lg:py-1 -lg:hover:bg-red cursor-pointer">
				Podcasts
			</router-link>
		</li>
		<li>
			<router-link :to="{ name: 'projects' }" class="-lg:px-4 -lg:py-1 -lg:hover:bg-red cursor-pointer">
				Projecten
			</router-link>
		</li>
		<li>
			<router-link :to="{ name: 'shop' }" class="-lg:px-4 -lg:py-1 -lg:hover:bg-red cursor-pointer">
				Shop
			</router-link>
		</li>
		<li>
			<router-link :to="{ name: 'help' }" class="-lg:px-4 -lg:py-1 -lg:hover:bg-red cursor-pointer text-green">
				Help mee
			</router-link>
		</li>
	</ul>
</template>

<script>
import headerMixin from "@/mixins/headerMixin";
export default {
	name: "Links",
	mixins: [headerMixin]
}
</script>

<style scoped>

</style>
