<template>
  <q-layout view="lHh Lpr lFf">
    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script lang="ts" setup>
</script>

<style scoped lang="scss">
.q-page-container {
  background: rgb(10, 10, 0);
  background: linear-gradient(135deg, rgba(0, 0, 0, 0.7) 0%, rgba(0, 0, 0, 0.7) 50%, rgba(100, 100, 97, 0.7) 100%);
}
</style>
