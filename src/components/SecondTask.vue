<script setup lang="ts">
import Card from '../ui/Card.vue';
</script>

<template>
<div class="block">
  <Card/>
  <Card/>
  <Card/>
  <Card/>
  <Card/>
  <Card/>
  <Card/>
  <Card/>
  <Card/>
  <Card/>
  <Card/>
  <Card/>
  <Card/>
  <Card/>
  <Card/>
  <Card/>
  <Card/>
  <Card/>
  <Card/>
  <Card/>
  
</div>
</template>

<style scoped>
.block {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  padding: .5rem;
  color: black;
  text-align: center;
  width: 942px;
  margin: auto;
}
</style>