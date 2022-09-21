<template>
	<!-- Navbar start -->
	<navbar-element></navbar-element>
	<!-- Navbar end -->

	<!-- Rendered view start -->
	<home-view></home-view>
	<!-- Rendered view end -->

	<!-- Footer start -->
	<footer-element></footer-element>
	<!-- Footer end -->
</template>

<script>
import NavbarElement from '@/components/NavbarElement.vue';
import FooterElement from '@/components/FooterElement.vue';
import HomeView from '@/HomeView.vue';

export default {
	components: {
		HomeView,
		FooterElement,
		NavbarElement
	}
}
</script>

<style>

</style>
