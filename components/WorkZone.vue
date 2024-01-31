<script setup>
const { data } = await useFetch("/api/list");
const items = data._rawValue.data;
</script>

<template>
  <div class="py-20">
    <div class="flex flex-col mx-auto max-w-[1200px]">
      <h2 class="text-[38px] font-bold leading-[54px]">
        Зоны работы на складе
      </h2>
      <h4 class="pb-10 font-normal text-[24px] leading-[36px]">
        Информацию об открытых позициях вам расскажет менеджер в процессе
        собеседования.
      </h4>
      <ul
        class="grid grid-cols-[repeat(auto-fit,_580px)] grid-rows-[auto] gap-x-[40px] gap-y-[24px] justify-center m-0 p-0 max-w-[1200px] list-none"
      >
        <div v-for="(item, index) in items" :key="index">
          <li
            class="rounded-3xl bg-[#FFF] shadow-[0_4px_16px_0_rgba(0,0,0,0.25)] flex flex-row px-4 py-4 gap-10 h-[288px]"
          >
            <img :src="item.image" />
            <div>
              <h4 class="mb-6 text-[23.664px] font-bold leading-[31.98px]">
                {{ item.title }}
              </h4>
              <ul class="flex flex-col gap-2">
                <li v-for="(item, index) in item.list" :key="index" class="list-disc">
                  <p class="tracking-tighter font-normal">{{ item }}</p>
                </li>
              </ul>
            </div>
          </li>
        </div>
      </ul>
    </div>
  </div>
</template>
