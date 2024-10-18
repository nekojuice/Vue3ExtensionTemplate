<template>
  <div>
    <div class="sidenav p-0 flex justify-content-center flex-wrap">
      <Button v-tooltip="'說明'" class="h-2rem w-2rem flex align-items-center justify-content-center" icon="pi pi-ellipsis-v" severity="secondary" />
    </div>
    <div class="main">
      <Button class="w-10rem" label="貓咪說嗨"></Button>
    </div>
  </div>
</template>
<script setup>
import Button from 'primevue/button';
</script>
<style scoped>
.sidenav {
  height: 90%;
  width: 32px;
  position: fixed;
  z-index: 1;
  overflow: hidden;
}
.main {
  margin-left: 64px;
  display: flex;
  flex-direction: column;
  height: 100%;
}
</style>
