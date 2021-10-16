<script lang="ts">
import { defineComponent } from 'vue'

const Image = defineComponent({
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
export default Image;
</script>

<template>
  <img :alt="alt" :src="src" />
</template>
