<script setup lang="ts"></script>

<template>
  <TresMesh>
    <TresMeshBasicMaterial />
    <!-- change args props see mesh don't update -->
    <TresBoxGeometry :args="[2, 2, 2]" />
  </TresMesh>
</template>
