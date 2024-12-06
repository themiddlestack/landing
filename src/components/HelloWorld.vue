<script setup>

</script>

<template>
  <div class="greetings">
    <h1 class="green name">MIDDLE STACK</h1>
    <h3 class=title-text>
      <span>Разработка SPA.</span> <br />
      <span class="first-aria">Backend серверов.</span> <br />
      <span class="second-aria">Телеграм ботов.</span>
    </h3>
  </div>
</template>

<style scoped>
@media (max-width: 1024px) {
    .name {
      transform: translateX(30px);
    }
}
.name {
  font-famaly: "Ubuntu";
  font-weight: 900;
      color: rgb(0, 255, 200);
}
h1 {
  transform: translateX(-100px);
  font-weight: 500;
  font-size: 2.6rem;
  text-wrap: nowrap;
  position: relative;
  top: -10px;
}
h3 {
  font-size: 1.2rem;
}
.greetings h1,
.greetings h3 {
  text-align: center;
}
@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
.first-aria {
  display: inline-block;
  transform: translateX(30px);
}
.second-aria {
  display: inline-block;
  transform: translateX(60px);
}
.title-text {
  transform: translateX(-15px)
}
.first-text {
  color: rgba(0, 255, 195, .5);
}
.second-text {
  color: rgba(255, 165, 0, .5);
}
.three-text {
  color: rgba(255, 0, 0, .5);
}
</style>
