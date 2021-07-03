<template>
  <div>
    <Hero />
    <LargeCardDisplay
      v-for="cardInfo in largeCardInfo"
      :key="cardInfo.id"
      :cardsSection="cardInfo"
    /> 
 
  </div>
</template>

<script>
import { largeCardSections } from "@/assets/data.js"
export default {
  data(){
    return {
      largeCardInfo: largeCardSections,
    }
  },
  mounted() {
    console.log(this.largeCardInfo)
  },
}
</script>

<style>
</style>