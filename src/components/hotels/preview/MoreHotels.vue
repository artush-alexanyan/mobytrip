<template>
  <div class="bg-[#E8E9F3]">
    <div class="container-w pt-[60px] pb-[100px]">
      <h2 class="text-black font-extrabold text-x26 mb-[20px]">Your search</h2>

      <div class="content flex flex-wrap gap-5">
        <HotelItem />
        <HotelItem />
        <HotelItem />
        <HotelItem />
      </div>
    </div>
  </div>
</template>

<script>
import HotelItem from "@/components/hotels/preview/HotelItem.vue";
export default {
  name: "MoreHotels",
  components:{
    HotelItem
  }
}
</script>

<style scoped>

</style>