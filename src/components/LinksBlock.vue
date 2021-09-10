<template>
  <section class="my-8">
        <div class="container mx-auto">
            <div class="grid grid-cols-1 md:grid-cols-2 space-y-4 md:space-y-0">
                <div class="h-64 bg-yellow-100 md:mr-8 flex justify-center items-center relative">
                    <div class="" style="z-index: 1;">
                        <h2 class="text-2xl text-gray-900">Don't have a NEAR account?</h2>
                        <a href="#" class="mt-4 mx-auto block border border-gray-900 text-center hover:bg-gray-900 hover:text-white transition-colors duration-500 py-2 px-4">
                            Sign up
                        </a>
                    </div>
                    <img src="@/assets/laptop-croped.png" alt="laptop" class="absolute h-72" style="z-index: 0; bottom: 0px; left: 0px;">
                    <img src="@/assets/plant-croped.png" alt="laptop" class="hidden md:block absolute h-full" style="z-index: 0; top: 0px; right: 0px;">
                </div>
                <div class="h-64 bg-yellow-100 md:ml-8 flex justify-center items-center relative">
                    <img src="@/assets/glass-croped.png" alt="laptop" class="absolute" style="z-index: 0; bottom: 0px; left: 0px;">
                    <div class="" style="z-index: 1;">
                        <h2 class="text-2xl text-gray-900">Add new book to NEAR Library</h2>
                        <a href="#" class="mt-4 mx-auto block border border-gray-900 text-center hover:bg-gray-900 hover:text-white transition-colors duration-500 py-2 px-4">
                            Add book
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style>

</style>