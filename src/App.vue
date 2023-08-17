<script setup lang="ts">
import { TresCanvas } from '@tresjs/core'
import Box from './Box.vue'
import { OrbitControls } from '@tresjs/cientos';
</script>

<template>
  <TresCanvas window-size>
    <OrbitControls />
    <Box></Box>
  </TresCanvas>
</template>
 
