<template>
  <div class="container">
    <Presentation />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Presentation } from './components/organisms'

export default defineComponent({
  components: { Presentation }
})
</script>

<style lang="scss" scoped>
.container {
  margin: 5rem;
}
</style>
