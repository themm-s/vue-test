<script lang="ts">
export default {
  data() {
    return {
      sections: [
        { 
          title: 'Секция', 
          content: 'Проверка однострочного текста', 
          open: false 
        },
        { 
          title: 'Секция 2', 
          content: 'lorem lorem lorem lorem loremlorem lorem lorem lorem lorem lorem lorem lorem lorem lorem lorem', 
          open: false 
        },
        { 
          title: 'Секция 3', 
          content: 'lorem lorem loremlorem lorem lorem lorem lorem lorem lorem lorem lorem lorem lorem', 
          open: false 
        },
        { 
          title: 'Секция 4', 
          content: 'lorem lorem lorem lorem lorem lorem lorem lorem lorem lorem lorem lorem lorem lorem', 
          open: false 
        },
      ]
    };
  },
  methods: {
    toggleSection(index: number) {
      this.sections[index].open = !this.sections[index].open;
    }
  }
};
</script>

<template>
  <div class="block">
    <div v-for="(section, index) in sections" :key="index" class="section">
      <div @click="toggleSection(index)" class="title"> 
        {{ section.title }}
      </div>
      <div v-if="section.open" class="content">
        {{ section.content }}
      </div>
    </div>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}

.section {
  border: 1px solid #fff;
  margin: 5px;
}

.block {
  width: 560px;
  word-break: normal;
  text-align: center;
}

.content {
  padding: .5rem;
  text-align: left;
}
</style>
