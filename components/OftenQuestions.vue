<script setup>
const props = defineProps({
  items: {
    Array,
  },
});

const list = ref(
  props.items.map((item) => {
    return {
      ...item,
      open: false,
    };
  })
);

const toggleModal = (item) => {
  item.open = !item.open
}


</script>

<template>
  <div id="questions" class="py-20 bg-[#F1F4F5]">
    <div class="flex flex-col mx-auto max-w-[1200px]">
      <h2 class="text-[38px] leading-[54px] font-bold w-full">
        Часто задаваемые вопросы
      </h2>
      <div v-for="(item, index) in list" :key="index" class="max-w-[1200px]">
        <h3 class="py-6 text-[22px] leading-[32px] font-bold">
          <button
            type="button"
            class="cursor-pointer flex flex-row justify-between w-full"
            @click="toggleModal(item)"
          >
            <span>{{ item.title }}</span>
            <NuxtImg :class="[item.open ? 'rotate-45' : 'rotate-0']" class="w-10 h-10 transition-all ease-linear duration-100 hover:rotate-45" :src="item.icon" />
          </button>
        </h3>
        <div :class="{hidden: !item.open}">
          <div>
            <p class="font-normal text-[18px] leading-[31px]">{{ item.text }}</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
