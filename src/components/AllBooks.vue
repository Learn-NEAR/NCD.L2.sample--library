<template>
  <section class="my-8">
        <div class="container mx-auto px-4 md:px-0">
            <div class="block md:flex items-center justify-between">
                <div class="flex items-center my-8 space-x-8">
                    <h3 class="text-gray-900 text-2xl">Books</h3>
                    <hr class="mt-1 w-56 border border-gray-900">
                </div>
                <div class="ml-auto md:ml-0">
                    <ul class="flex items-center space-x-4 text-blue-500">
                        <li class="">
                            <a href="#" class="flex items-center hover:underline">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 16V4m0 0L3 8m4-4l4 4m6 0v12m0 0l4-4m-4 4l-4-4" />
                                </svg>
                                Name
                            </a>
                        </li>
                        <li class="">
                            <a href="#" class="flex items-center hover:underline">
                                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 16V4m0 0L3 8m4-4l4 4m6 0v12m0 0l4-4m-4 4l-4-4" />
                                </svg>
                                Date
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="space-y-6">
                <div class="grid grid-cols-2 md:grid-cols-6">
                    <book/>
                    <book/>
                    <book/>
                    <book/>
                    <book/>
                    <book/>
                    <book/>
                    <book/>
                    <book/>
                    <book/>
                    <book/>
                    <book/>
                    <book/>
                    <book/>
                    <book/>
                    <book/>
                    <book/>
                    <book/>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
import Book from './Book.vue'
export default {
  components: { Book },

}
</script>

<style>

</style>