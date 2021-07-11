<template>
  <div class="container">
    <Container>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione deserunt
      at reiciendis labore quaerat ipsam excepturi repellendus animi numquam
      quidem, placeat cum quas dolores architecto et nam vero, aut eveniet!
    </Container>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Container } from './components/bosons'

export default defineComponent({
  components: { Container }
})
</script>

<style lang="scss" scoped>
.container {
  margin: 5rem;
}
</style>
