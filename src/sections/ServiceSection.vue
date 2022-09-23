<template>
    <!-- Services section start -->
	<section id="services-section" class="px-12 lg:px-32 py-16 relative overflow-hidden">
        <!-- Text wrapper start -->
        <div class="flex gap-8 flex-col md:flex-row">
            <!-- Main text start -->
            <h1 class="uppercase text-5xl mb-4 font-semibold ">
                OUR SERVICES
            </h1>
            <p class="capitalize xl:w-1/2 text-stone-500 mb-8">
                Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                Cupiditate iure rem harum, quam magnam accusamus inventore incidunt nihil, fuga soluta earum!
                Voluptatibus, recusandae. Cumque sequi ullam, nostrum voluptatum eius saepe.
            </p>
            <!-- Main text end -->
        </div>
        <!-- Text wrapper end -->

        <!-- Services start -->
        <div class="flex flex-col md:flex-row md:gap-8">
            <!-- Wedding service start -->
            <div class="flex flex-row md:flex-col justify-between md:justify-start items-center md:items-start my-8 md:w-1/3">
                <img src="@/assets/services/wedding.png" alt="Wedding" class="-z-50 md:mb-4">
                <div class="w-2/3 text-right md:text-left md:w-full">
                    <h1 class="uppercase text-2xl font-semibold">
                        Wedding
                    </h1>
                    <p class="capitalize text-stone-500">
                        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Earum, neque?
                    </p>
                </div>
            </div>
            <!-- Wedding service end -->

            <!-- Wedding service start -->
            <div class="flex flex-row md:flex-col justify-between items-center md:items-start my-8 md:w-1/3">
                <div class="w-2/3 text-left md:w-full md:order-2">
                    <h1 class="uppercase text-2xl font-semibold">
                        Lifestyle
                    </h1>
                    <p class="capitalize text-stone-500">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet, ratione!
                    </p>
                </div>
                <img src="@/assets/services/lifestyle.png" alt="Lifestyle" class="-z-50 md:mb-4 md:order-1">
            </div>
            <!-- Wedding service end -->

            <!-- Wedding service start -->
            <div class="flex flex-row md:flex-col justify-between items-center md:items-start my-8 md:w-1/3">
                <div class="w-1/3">
                    <img src="@/assets/services/moments.png" alt="Moments" class="-z-50 md:mb-4">
                </div>
                <div class="w-2/3 text-right md:text-left md:w-full">
                    <h1 class="uppercase text-2xl font-semibold">
                        Moments
                    </h1>
                    <p class="capitalize text-stone-500">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Exercitationem, molestias.
                    </p>
                </div>
            </div>
            <!-- Wedding service end -->
        </div>
        <!-- Services end -->

        <!-- Circle start -->
        <div class="bg-neutral-300 h-64 w-64 rounded-full absolute top-0 -right-20 mt-16 -z-20"></div>
        <!-- Circle end -->
	</section>
	<!-- Services section end -->
</template>

<script>
export default {

}
</script>

<style>

</style>