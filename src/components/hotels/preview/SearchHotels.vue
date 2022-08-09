<template>
  <div class="bg-[#E8E9F3]">
    <div class="container-w pt-[36px] sms:pt-[60px] pb-[40px] sms:pb-[100px]">
      <h2 class="text-black font-extrabold text-x26 mb-[20px]">Your search</h2>

      <div class="filters mb-[30px]">
        <Filters />
      </div>

      <div class="search-list">
        <p class="text-black font-extrabold text-lg mb-[20px] block lg:hidden">Choose your room</p>
        <SearchItem />
        <SearchItem />
        <SearchItem />
      </div>
    </div>
  </div>
</template>

<script>
import SearchItem from "@/components/hotels/preview/SearchItem.vue";
import Filters from "@/components/hotels/preview/Filters.vue";
export default {
  name: "SearchHotels",
  components: {
    Filters,
    SearchItem
  }
}
</script>

<style scoped>

</style>