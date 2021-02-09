<template>
  <div class="about">
    <h1>This is an about page</h1>
      <Cards msg="Esta es otra tarjeta"/>

  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import Cards from '@/components/Cards.vue'

export default {
  name: 'Home',
  components: {
    Cards
  }
}
</script>

