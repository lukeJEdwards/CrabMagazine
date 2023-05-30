<script setup lang="ts"></script>

<template>
  <router-view></router-view>
</template>

<style>
body::after {
  content: "";
  background-color: #000000;
  background-image: url("assets/subtle-grunge.png");
  opacity: 0.2;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  position: absolute;
  z-index: -1;
}
</style>
