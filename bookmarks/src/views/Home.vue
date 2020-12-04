<template>
  <div class="home container">
    <div class="row">
      <template v-if="!loader">
        <Cards v-for="i in 10" :key="i"/>
      </template>
      <template v-if="fetchSites">
        yuklanmoqda...
      </template>
    </div>
  </div>
</template>

<script>

import Cards from '@/components/card/Cards'

export default {
  name: 'Home',
  components: {
      Cards
  },
  data: () => ({
    loader: false
  }),
  async created(){
    await this.fetchSites()
  },
  methods:{
    async fetchSites(){
      this.loader = false
      // setTimeout(function () {
      //   this.loader = false
      //   console.log("stop")
      // }, 5000)

    }
  }
}
</script>

<style scoped>
.row{
  display: flex;
  justify-content: space-between;
  align-items: center;
}
</style>
