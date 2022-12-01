<template>
  <div class="home">
      <NewBookForm />
      <BestSellerList />
      <NewReleasesList />
  </div>
</template>

<script>
  import NewBookForm from '@/components/NewBookForm'
  import BestSellerList from '@/components/BestSellerList'
  import NewReleasesList from '@/components/NewReleasesList'

  export default {
    components: {
      NewBookForm,
      BestSellerList,
      NewReleasesList
    }
  }
</script>

<style>

</style>