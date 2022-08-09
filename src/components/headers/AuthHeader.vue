<template>
  <header class="bg-blue">
    <div class="container-w flex items-center justify-between py-8">
      <span class="flex">
        <img src="@/assets/images/mobytrip.png" alt="image">
      </span>

      <div class="hidden sms:flex">
        <button class="bg-white py-[9px] px-[41px] text-blue rounded-[10px] font-semibold">Log in</button>
      </div>

      <span class="flex sms:hidden">
        <img src="@/assets/images/sort.png" alt="">
      </span>
    </div>
  </header>
</template>

<script>
export default {
  name: "AuthHeader"
}
</script>

<style scoped>

</style>