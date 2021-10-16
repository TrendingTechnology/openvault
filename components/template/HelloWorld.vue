<script lang="ts">
import { defineComponent } from 'vue'
import MoreInformation from '@/components/organism/MoreInformation.vue'
import SimpleCounter from '@/components/molecule/SimpleCounter.vue'

const HelloWorld = defineComponent({
  components: { MoreInformation, SimpleCounter },
  props: {
    msg: {
      required: false,
      type: String,
      default: "Hello World"
    }
  },
})

export default HelloWorld;
</script>

<template>
  <h1>{{ msg }}</h1>
  <MoreInformation />
  <SimpleCounter />
</template>