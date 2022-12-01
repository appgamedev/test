<template>
  <div class="myBooks">
      <ReadingList />
      <div>
          <a href="/addBook">add Book To Reading List</a>
  </div>
  </div>
</template>

<script>
import ReadingList from '@/components/ReadingList'

export default {
    components: {
      ReadingList,
    }
}
</script>

<style>

</style>