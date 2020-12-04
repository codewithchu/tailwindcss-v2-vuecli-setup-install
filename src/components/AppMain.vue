<template>
	<div class="wrapper">
		<div class="card">
			<h1 class="font-bold text-6xl ">Vues With TailwindCSS v2</h1>
			<h2 class="text-3xl font-bold">Using VueCLI</h2>
		</div>
	</div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.wrapper {
	@apply flex justify-center items-center h-screen text-center text-emerald-500 bg-gray-100;
}
.card {
	@apply rounded-lg border border-emerald-300 bg-emerald-100 p-10 shadow-lg;
}
</style>
