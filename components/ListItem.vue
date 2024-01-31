<script setup>
const props = defineProps({
  item: {
    Array,
  },
});
console.log(item)
</script>

<template>
  <div>
    <ul v-for="(item, index) in item" :key="index">
        <li>{{ item.list }}</li>
    </ul>
  </div>
</template>
