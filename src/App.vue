<template>
  <div class="container">
    <Service
      title="Aristoteles"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Nobis alias totam debitis quia eveniet sapiente perspiciatis quibusdam quod, accusantium neque adipisci asperiores. Accusamus quo et aut adipisci minima nemo iusto."
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Service } from './components/molecules'

export default defineComponent({
  components: { Service }
})
</script>

<style lang="scss" scoped>
.container {
  margin: 2rem;
  width: 300px;
}
</style>
