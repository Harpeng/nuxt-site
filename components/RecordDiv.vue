<template>
  <div
    class="mt-[80px] grid grid-cols-[repeat(5,_1fr)] grid-rows-[repeat(5,_1fr)] gap-0 bg-[#E3E9ED] overflow-hidden"
  >
    <div class="z-[50] row-start-2 row-end-5 col-start-2 col-end-5 text-white">
      <div class="flex flex-col gap-8">
        <h2 class="max-w-[646px] text-[54px] font-bold leading-[72px]">
          Вы приглашены на онлайн-собеседование.
        </h2>
        <p class="max-w-[308px] text-[24px] leading-[36px] font-normal">
          Просим Вас пройти регистрацию. До встречи!
        </p>
        <NuxtLink to="https://pr-lg.ru/" target="_blank" >
          <ButtonPage
            class="mt-5 mb-2.5 h-20 px-20 text-2xl font-bold w-[255px] box-content"
          />
        </NuxtLink>
      </div>
    </div>
    <NuxtImg
      class="row-start-1 row-end-6 col-start-1 col-end-6 h-[640px] object-cover relative overflow-hidden"
      src="/register.png"
    />
    <NuxtImg
      class="absolute left-[300px] top-[500px] w-[45px] h-[101.25px] max-[1763px]:left-[250px] max-[1536px]:left-[200px] max-[1268px]:left-[150px]"
      src="/Frame.svg"
    />
  </div>
</template>
