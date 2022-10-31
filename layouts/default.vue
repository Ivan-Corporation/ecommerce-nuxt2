<template>
	<v-app dark :style="{ backgroundColor: $vuetify.theme.dark ? '#0a0514' : 'white' }">
		<v-main>

			<DesktopNav />
			<Nuxt />
		</v-main>
	</v-app>
</template>

<script>
export default {};
</script>
