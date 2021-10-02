<script lang="ts">
import { defineComponent } from 'vue'
import HelloWorld from '@/components/template/HelloWorld.vue'
import Image from '@/components/atom/Image.vue';

const Home = defineComponent({
  components: { HelloWorld, Image }
})
export default Home;
</script>

<template>
  <Image alt="OpenVault" src="/logo/emblem-with-text.svg" />
  <HelloWorld msg="Hello Vue 3 + TypeScript + Vite" />
</template>
