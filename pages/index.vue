<template>
  <div class="nuxt-time">
    <h1>Nuxt Time</h1>

    <NuxtTime
      :datetime="Date.now()"
      year="numeric"
      month="long"
      day="numeric"
      hour="2-digit"
      minute="2-digit"
      hour-cycle="h24"
      locale="hy-AM"
    />
  </div>
</template>

<script setup lang="ts"></script>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  background-color: #000;
}

.nuxt-time {
  text-align: center;
  color: white;
  margin-top: 30px;
}
</style>
