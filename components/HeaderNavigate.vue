<script setup>
</script>

<template>
  <nav>
    <ul
      class="flex flex-row justify-end gap-7 text-sm font-bold text-[#212121]"
    >
      <li>
        <NuxtLink :to="{path: '/', hash: '#benefit'}" class="cursor-pointer"
          >Преимущества</NuxtLink
        >
      </li>
      <li>
        <NuxtLink :to="{path: '/', hash: '#questions'}" class="cursor-pointer"
          >Вопросы</NuxtLink
        >
      </li>
      <li>
        <NuxtLink to="https://pr-lg.ru/" target="_blank" class="cursor-pointer"
          >Регистрация</NuxtLink
        >
      </li>
    </ul>
  </nav>
</template>
