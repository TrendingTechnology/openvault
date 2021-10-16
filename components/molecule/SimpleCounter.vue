<script lang="ts">
import { defineComponent, ref } from 'vue'
import Button from '@/components/atom/Button.vue'

const SimpleCounter = defineComponent({
  components: { Button },
  setup() {
    const count = ref(0)
    return { count }
  }
})

export default SimpleCounter;
</script>

<template>
  <Button @click="count++">count is: {{ count }}</Button>
</template>