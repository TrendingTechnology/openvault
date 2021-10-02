<script lang="ts">
import { defineComponent } from 'vue'

const Button = defineComponent({
  props: {
    src: {
      required: true,
      type: String
    },
    alt: {
      required: false,
      type: String
    }
  }
})
export default Button;
</script>

<template>
  <button type="button"><slot /></button>
</template>
