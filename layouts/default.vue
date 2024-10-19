<script setup lang="ts">

</script>

<template>
  <section class="grid" style="min-height: 100vh">
    <LayoutSidebar />
    <!-- имя компонента основано на его пути в директориях и имени файла, при этом повторяющиеся сегменты будут удалены -->
    <div>
      <slot />
    </div>
  </section>
</template>

<style scoped>
.grid {
  display: grid;
  grid-template-columns: 1fr 6fr;
}
</style>