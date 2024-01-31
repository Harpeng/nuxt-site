<template>
  <div class="flex flex-row my-20 max-w-[1200px] rounded-3xl bg-[#F1F4F5] mx-auto">
    <div class="flex flex-col py-[60px] pl-[60px] pr-[128px]">
      <h3 class="max-w-[399px] text-[38px] leading-[54px] font-bold text-[#212121] mb-2.5">Не упустите шанс подняться по карьерной лестнице!</h3>
      <div class="bg-[url('/line.svg')] w-[50px] h-[3px] mb-[27px]"></div>
      <p class="max-w-[382px] font-normal text-[20px] leading=[31pxz] text-[#555]">
        Зарегистрируйтесь и позвольте нашим менеджерам предложить вам самые
        подходящие вакансии.
      </p>
      <NuxtLink to="https://pr-lg.ru/" target="_blank">
        <ButtonPage class="mt-[60px] font-normal text-[14.75px] px-[60px] py-[21.5px] max-w-[278.28px]" />
      </NuxtLink>
    </div>
    <NuxtImg
      class="rounded-3xl object-cover w-full max-w-[600px]" src="/imageBlock.png"
    />
  </div>
</template>
