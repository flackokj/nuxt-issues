<template>
  <HomeIcon class="w-5 h-5" />
  <h1>{{myName}}</h1>
</template>

<script setup>
  import {HomeIcon} from '@heroicons/vue/24/outline'

  const myName = ref('username')
</script>
