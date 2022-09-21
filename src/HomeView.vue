<template>

	<!-- Main section start -->
	<main-section></main-section>
	<!-- Main section end -->

	<!-- About section start -->
	<about-section></about-section>
	<!-- About section end -->

	<!-- Services section start -->
	<service-section></service-section>
	<!-- Services section end -->

</template>

<script>
import MainSection from '@/sections/MainSection.vue';
import AboutSection from '@/sections/AboutSection.vue';
import ServiceSection from '@/sections/ServiceSection.vue';

export default {
	components: {
		MainSection,
		AboutSection,
		ServiceSection
	}
}
</script>

<style scoped>


</style>