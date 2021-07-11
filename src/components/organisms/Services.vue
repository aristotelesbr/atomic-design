<template>
  <div class="services">
    <Service
      title="Front End"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi est autem quas esse debitis excepturi nisi, optio, culpa veritatis quam explicabo delectus asperiores sit. Facere quia saepe minus eaque nemo?"
    />
    <Service
      title="Backend"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi est autem quas esse debitis excepturi nisi, optio, culpa veritatis quam explicabo delectus asperiores sit. Facere quia saepe minus eaque nemo?"
    />
    <Service
      title="Devops"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi est autem quas esse debitis excepturi nisi, optio, culpa veritatis quam explicabo delectus asperiores sit. Facere quia saepe minus eaque nemo?"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Service } from '@/components/molecules'

export default defineComponent({
  components: { Service }
})
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>
