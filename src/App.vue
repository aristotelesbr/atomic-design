<template>
  <div class="container">
    <Home>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione deserunt
      at reiciendis labore quaerat ipsam excepturi repellendus animi numquam
      quidem, placeat cum quas dolores architecto et nam vero, aut eveniet!
    </Home>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Home } from './components/templates'

export default defineComponent({
  components: { Home }
})
</script>

<style lang="scss" scoped>
.container {
  margin: 5rem;
}
</style>
