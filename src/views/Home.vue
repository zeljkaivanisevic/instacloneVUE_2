<template>
<div class="container">
  <div class="row">
    <div class="col-1"></div>

    <div class="col-7">
      <InstagramCard/>
      
    </div>

    <div class="col-3">
    <Stories/>
    <Suggestions/>


    </div>
  </div>
  </div>
</template>

<script>
import InstagramCard from '@/components/InstagramCard.vue'
import Stories from '@/components/Stories.vue'
import Suggestions from '@/components/Suggestions.vue'
export default {
  name: 'home',
  components: {
    InstagramCard,
    Stories,
    Suggestions
  }
}


</script>






<style lang="scss">
.card-body {
  padding: 0px;
}

.card {
  margin-bottom: 20px;
}
</style>