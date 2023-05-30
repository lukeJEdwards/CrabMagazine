<script setup lang="ts"></script>

<template>
  <router-view></router-view>
</template>

<style>
@font-face {
  font-family: "Alta California W00";
  src: url(".assets/fonts/Alta_California_W00/c104cc4d10d99dcb312a3b4e19059e33.eot"); /* IE9*/
  src: url(".assets/fonts/Alta_California_W00/c104cc4d10d99dcb312a3b4e19059e33.eot?#iefix")
      format("embedded-opentype"),
    /* IE6-IE8 */
      url(".assets/fonts/Alta_California_W00/c104cc4d10d99dcb312a3b4e19059e33.woff2")
      format("woff2"),
    /* chrome、firefox */
      url(".assets/fonts/Alta_California_W00/c104cc4d10d99dcb312a3b4e19059e33.woff")
      format("woff"),
    /* chrome、firefox */
      url(".assets/fonts/Alta_California_W00/c104cc4d10d99dcb312a3b4e19059e33.ttf")
      format("truetype"),
    /* chrome、firefox、opera、Safari, Android, iOS 4.2+*/
      url(".assets/fonts/Alta_California_W00/c104cc4d10d99dcb312a3b4e19059e33.svg#Alta California W00")
      format("svg"); /* iOS 4.1- */
}

body::after {
  content: "";
  background-color: #000000;
  background-image: url(assets/subtle-grunge.png);
  opacity: 0.2;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  position: absolute;
  z-index: -1;
}
</style>
