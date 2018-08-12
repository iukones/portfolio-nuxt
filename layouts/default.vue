<template>
  <div>
    <TheHeader/>
    <section class="ae-container-fluid rk-main">
      <nuxt/>
    </section>
    <TheFooter/>
  </div>
</template>

<script>
import TheHeader from '@/components/TheHeader/TheHeader'
import TheFooter from '@/components/TheFooter/TheFooter'
export default {
  components: {
    TheHeader,
    TheFooter
  }
}
</script>



