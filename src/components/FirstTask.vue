<script setup lang="ts">
import Accordion from '../ui/Accordion.vue';
import Content from '../ui/Content.vue'
</script>


<template>
  <div class="container">
    <div>
      <Content/>
    </div>
    <div>
      <Accordion />
    </div>
  </div>
</template>

<style scoped>
.container {
  display: flex;
  justify-content: center;
  width: auto;
  margin: auto;
}
</style>