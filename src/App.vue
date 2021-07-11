<template>
  <div class="container"><SocialNetworks /></div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { SocialNetworks } from './components/molecules'

export default defineComponent({
  components: { SocialNetworks }
})
</script>

<style lang="scss" scoped>
.container {
  width: 300px;
}
</style>
