<script lang="ts">
import { defineComponent } from 'vue'

const Button = defineComponent({
  props: {
    className: {
      type: String,
      required: false,
      default: "bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 border border-blue-700 rounded"
    }
  },
})
export default Button;
</script>

<template>
  <button type="button" :class="className"><slot /></button>
</template>