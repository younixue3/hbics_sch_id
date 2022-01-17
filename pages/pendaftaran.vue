<template>
  <div class=" bg-gray-50 h-screen">
    <header-rdev />
        <NuxtChild />
    <footer-rdev />
  </div>
</template>

<script>
import FooterRdev from '~/components/FooterRdev.vue'
export default {
  components: { FooterRdev },
  name: 'PendaftaranPage'
}
</script>
