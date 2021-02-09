<template>
  <div class="home">
    <Cards msg="Esta es una tarjeta"/>
    <Cards msg="Esta es otra tarjeta"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Cards from '@/components/Cards.vue'

export default {
  name: 'Home',
  components: {
    Cards
  }
}
</script>
