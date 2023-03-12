<template>
    <!-- Services section start -->
	<section id="services-section" class="px-12 lg:px-32 py-16 relative overflow-hidden">
        <!-- Text wrapper start -->
        <div class="flex gap-8 flex-col md:flex-row">
            <!-- Main text start -->
            <h1 class="uppercase text-5xl mb-4 font-semibold ">
                ABOUT THE WEB
            </h1>
            <p class="capitalize xl:w-1/2 text-stone-500 mb-8">
                This webpage will help students find their online study buddy through matchmaking system.
                They will be able to interact with other students with the same course or subjects through 
                different ways.
            </p>
            <!-- Main text end -->
        </div>
        <!-- Text wrapper end -->

        <!-- Services start -->
        <div class="flex flex-col md:flex-row md:gap-8">
            <!-- Video chat service start -->
            <div class="flex flex-row md:flex-col justify-between md:justify-start items-center md:items-start my-8 md:w-1/3">
                <img src="@/assets/services/videosym(2).jpg" alt="Wedding" class="-z-50 md:mb-4">
                <div class="w-2/3 text-right md:text-left md:w-full">
                    <h1 class="uppercase text-2xl font-semibold">
                        VIDEO CHAT
                    </h1>
                    <p class="capitalize text-stone-500">
                        Students will be able to connect with their study buddy through our built-in
                        video chat system with messaging capability.
                    </p>
                </div>
            </div>
            <!-- Video chat service end -->

            <!-- Matchmaking service start -->
            <div class="flex flex-row md:flex-col justify-between items-center md:items-start my-8 md:w-1/3">
                <div class="w-2/3 text-left md:w-full md:order-2">
                    <h1 class="uppercase text-2xl font-semibold">
                        MATCHMAKING SYSTEM
                    </h1>
                    <p class="capitalize text-stone-500">
                        Our built-in matchmaking system will automatically find
                        a study buddy partner for students with the same course or subjects
                    </p>
                </div>
                <img src="@/assets/services/matchmaking(2).jpg" alt="Lifestyle" class="-z-50 md:mb-4 md:order-1">
            </div>
            <!-- Matchmaking service end -->

            <!-- Studytool service start -->
            <div class="flex flex-row md:flex-col justify-between items-center md:items-start my-8 md:w-1/3">
                <div class="w-1/3">
                    <img src="@/assets/services/studytool(1).jpg" alt="Moments" class="-z-50 md:mb-4">
                </div>
                <div class="w-2/3 text-right md:text-left md:w-full">
                    <h1 class="uppercase text-2xl font-semibold">
                        Study Tool
                    </h1>
                    <p class="capitalize text-stone-500">
                        Our web contains different study tool that will help study partners with 
                        their studies. It includes flashcards, and practice quizzes according to
                        their lesson.
                    </p>
                </div>
            </div>
            <!-- Studytool service end -->
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