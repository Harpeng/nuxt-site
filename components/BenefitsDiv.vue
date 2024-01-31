<template>
  <div id="benefit" class="py-20 bg-[#E3E9ED] overflow-hidden">
    <div class="flex flex-col mx-auto max-w-[1200px]">
      <h2 class="text-[38px] leading-[54px] font-bold pb-10">
        Что вы получите работая в Профит-Лиге?
      </h2>
      <div
        class="grid gap-[20px] grid-cols-[repeat(6,_1fr)] grid-rows-[repeat(7,_1fr)]"
      >
        <div
          class="relative py-6 pl-6 pr-[120px] bg-[#fff] rounded-2xl row-start-1 row-end-3 col-start-1 col-end-4 flex flex-col"
        >
          <h3 class="text-[22px] font-bold leading-[32px] pb-4">
            Конкурентная заработная плата
          </h3>
          <div class="flex flex-row">
            <p class="z-10 text-[18px] font-normal leading-[24px]">
              Мы оцениваем ваши усилия и навыки и стремимся предоставить вам
              зарплату, которая соответствует вашему вкладу в компанию.
            </p>
            <NuxtImg
              class="absolute bottom-0 right-0 w-[180px] h-[180px] object-cover"
              src="/graphic.png"
            />
          </div>
        </div>
        <div
          class="relative py-6 pl-6 pr-[120px] bg-[#fff] rounded-2xl row-start-1 row-end-3 col-start-4 col-end-7 flex flex-col gap-4"
        >
          <h3 class="text-[22px] font-bold leading-[32px]">
            Комфортные условия труда
          </h3>
          <div class="flex flex-row">
            <p class="z-10 text-[18px] font-normal leading-[24px]">
              Мы стремимся создать здоровую и безопасную рабочую среду. У нас
              регулярно проводятся проверки и оценки условий труда с целью
              совершенствования нашего рабочего пространства.
            </p>
            <NuxtImg
              class="absolute bottom-0 right-0 w-[180px] h-[180px] object-cover"
              src="/chair.png"
            />
          </div>
        </div>
        <div
          class="max-w-[386.66px] relative py-6 pl-6 pr-[120px] bg-[#fff] rounded-2xl row-start-3 row-end-6 col-start-1 col-end-3 flex flex-col gap-4"
        >
          <h3 class="text-[22px] font-bold leading-[32px]">
            Интересные задачи
          </h3>
          <div class="flex flex-row">
            <p class="z-10 text-[18px] font-normal leading-[24px]">
              Ваша работа вносит реальный вклад в успех нашей компании. У вас
              будет возможность видеть непосредственное влияние своей работы и
              быть <br> частью чего-то большого
            </p>
            <NuxtImg
              class="absolute bottom-0 right-0 w-[180px] h-[180px] object-cover"
              src="/puzzle.png"
            />
          </div>
        </div>
        <div
          class="max-w-[386.66px] relative py-6 pl-6 bg-[#fff] rounded-2xl row-start-3 row-end-6 col-start-3 col-end-5 flex flex-col gap-4"
        >
            <h3
              class=" pr-[142.33px]  text-[22px] font-bold leading-[32px]"
            >
              Возможность работать в команде профессионалов
            </h3>
          <div class="flex flex-row gap-4">
            <p
              class="tracking-tight w-[266px] mr-4  z-10 text-[18px] font-normal leading-[24px]"
            >
              Работая с опытными коллегами, вы получите возможность развиваться
              как профессионал и расширять свои навыки и &nbsp; знания в&nbsp;специализированной сфере.
            </p>
            <div
              class="bg-no-repeat bg-cover bg-center bg-transparent absolute bottom-0 right-0 w-[140px] h-[180px] bg-[url('/guys.png')]"
            ></div>
          </div>
        </div>
        <div
          class=" max-w-[386.66px] relative py-6 pl-6 pr-[120px] bg-[#fff] rounded-2xl row-start-3 row-end-6 col-start-5 col-end-7 flex flex-col gap-4"
        >
          <h3 class="text-[22px] font-bold leading-[32px]">
            Насыщенная корпоративная жизнь
          </h3>
          <div class="flex flex-row">
            <p class="z-10 text-[18px] font-normal leading-[24px]">
              Мы регулярно проводим различные мероприятия, такие как семинары,
              тренинги, тематические вечеринки, праздничные мероприятия и
              командные выезды.
            </p>
            <div
              class="bg-no-repeat bg-cover bg-center bg-transparent absolute bottom-0 right-0 w-[180px] h-[180px] bg-[url('/girl.png')]"
            ></div>
          </div>
        </div>
        <div
          class="relative py-6 pl-6 pr-[120px] max-h-[144px] bg-[#fff] rounded-2xl row-start-6 row-end-8 col-start-1 col-end-7 flex flex-col gap-4"
        >
          <h3 class="text-[22px] font-bold leading-[32px]">
            Корпоративная скидка на все продаваемые бренды
          </h3>
          <div class="flex flex-row">
            <p class="break-words pr-6  z-10 text-[18px] font-normal leading-[24px]">
              Мы предоставляем персональные скидки для наших сотрудников,
              которые позволяют вам пользоваться&nbsp;нашими товарами и услугами на
              более выгодных условиях.
            </p>
            <NuxtImg
              class="bg-transparent absolute bottom-0 right-0 w-[140px] h-[140px] object-cover"
              src="/circle.png"
            />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
