<template>
  <div>
    <Gallery />
    <HotelInfo />
    <Issues />
    <MoreHotels />
  </div>

</template>

<script>
import Gallery from "@/components/hotels/preview/Gallery.vue";
import HotelInfo from "@/components/hotels/preview/HotelInfo.vue";
import Issues from "@/components/hotels/preview/Issues.vue";
import MoreHotels from "@/components/hotels/preview/MoreHotels.vue";
export default {
  name: "HotelPreview",
  components:{
    Gallery,
    HotelInfo,
    Issues,
    MoreHotels
  }
}
</script>