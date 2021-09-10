<template>
  <Header/>
  <info/>
  <last-added/>
  <links-block/>
  <all-books/>
</template>

<script>
import Header from '@/components/Header.vue'
import Info from '@/components/Info.vue'
import LastAdded from '@/components/LastAdded.vue'
import LinksBlock from '@/components/LinksBlock.vue'
import AllBooks from '@/components/AllBooks.vue'
export default {
    components: {
        Header,
        Info,
        LastAdded,
        LinksBlock,
        AllBooks
        }
}
</script>

<style>

</style>