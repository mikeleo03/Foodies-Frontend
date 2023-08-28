<template>
    <div id="app">
        <HeaderWeb />
        <Nuxt />
        <FooterWeb />
    </div>
</template>

<script>
// Memanggil component sesuai lokasi masing - masing file
import HeaderWeb from '@/components/HeaderWeb.vue'
import FooterWeb from '@/components/FooterWeb.vue'
export default {
  // Dideklarasikan agar dapat diakses oleh template
  components: {
    HeaderWeb,
    FooterWeb
  }
}
</script>

<style>
#app {
  margin: 1;
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}
</style>
