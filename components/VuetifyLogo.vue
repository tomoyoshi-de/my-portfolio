<template>
  <v-avatar
    :size="120"
  >
    <img
      class="VuetifyLogo"
      alt="Vuetify Logo"
      src="../static/photo.jpg"
    >
  </v-avatar>
</template>

<style>
.VuetifyLogo {
  width: 180px;
  transform: rotateY(560deg);
  animation: turn 3.5s ease-out forwards 1s;
}

@keyframes turn {
  100% {
    transform: rotateY(0deg);
  }
}
</style>
