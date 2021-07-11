<template>
  <div class="container">
    <Logo />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Logo } from './components/atoms'

export default defineComponent({
  components: { Logo }
})
</script>

<style lang="scss" scoped>
.container {
  width: 300px;
}
</style>
