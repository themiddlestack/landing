<script setup>
import WelcomeItem from './WelcomeItem.vue'
import CommunicationIcon from './icons/IconCommunication.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <CommunicationIcon />
    </template>
    <template #heading>
      <span class="title">Коммуникация</span>
    </template>
    Общение в мессаджерах и на форуме. 
    <a href="https://xss.is/escrow/" target="_blank" rel="noopener">Сделки - гарант.</a><br />
    Согласование технического задания, сроков реализации планов клиента. <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>
      <span class="title">Процесс</span>
    </template>
    Создаем структуру пректа. <br /> 
    Расписываем поэтапно методы реализации идей. <br />
    Настраиваем конфиги => Подбираем библиотеки => Пишем скрипты. 
    <a href=https://www.w3schools.com target="_blank" rel="noopener">www.w3schools</a>
    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>
      <span class="title">Экосистема</span>
    </template>
    Поддердиваемые ЯП -- <a href=#>JavaScript - TypeScript - Golang</a><br />

    Разработка ведется стого по специальной методологии. <br />

    Скрипты пишутся на проф уровне. <br /> На выходе получаете продукт, который можно масштабировать.<br />

    Поддерживаемые фреймворки 
    <a href="https://vuejs.org" target="_blank" rel="noopener">Vue</a>,
    <a href="https://react.dev" target="_blank" rel="noopener">React</a>,
    <a href="https://expressjs.com" target="_blank" rel="noopener">Express</a>,
    <a href="https://nestjs.com" target="_blank" rel="noopener">Nest</a>.

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>
      <span class="title">Техподдержка</span>
    </template>
    Работаем в штатном режиме. 
  </WelcomeItem>
</template>

<style scoped>
  .title {
    color: rgb(0, 255, 195);
  }
</style>