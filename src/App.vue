<template>
	<!-- Nav bar start -->
	<nav class="w-screen fixed bg-opacity-75 bg-white flex justify-between items-center py-4 px-20">
		<!-- Logo start -->
		<div>
			<p class="tracking-widest font-semibold">CHRIS</p>
			<p class="tracking-widest font-light">PHOTOGRAPHY</p>
		</div>
		<!-- Logo end -->

		<!-- Links start -->
		<div class="flex">
			<!-- Home router link -->
			<router-link to="/">
				<p class="mx-4">Home</p>
			</router-link>

			<!-- About router link -->
			<router-link to="/about">
				<p class="mx-4">About</p>
			</router-link>

			<!-- Explore router link -->
			<router-link to="/explore">
				<p class="mx-4">Explore</p>
			</router-link>
		</div>
		<!-- Links end -->

		<!-- Contact link start -->
		<button class="btn">
			Contact us
		</button>
		<!-- Contact link end -->
	</nav>
	<!-- Nav bar end -->

	<!-- Rendered view start -->
	<router-view/>
	<!-- Rendered view end -->
</template>

<script>

export default {
	
}
</script>

<style>

</style>
