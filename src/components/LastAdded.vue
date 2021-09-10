<template>
  <section class="">
        <div class="container mx-auto px-4 md:px-0">
            <div class="flex items-center my-8 space-x-8">
                <h3 class="text-gray-900 text-2xl">Last added books</h3>
                <hr class="mt-1 w-56 border border-gray-900">
            </div>
            <div class="grid grid-cols-2 md:grid-cols-6">
                <book/>
                <book/>
                <book/>
                <book/>
                <book/>
                <book/>
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