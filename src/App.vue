<template>
  <div class="container">
    <Services />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Services } from './components/organisms'

export default defineComponent({
  components: { Services }
})
</script>

<style lang="scss" scoped>
.container {
  margin: 5rem;
}
</style>
