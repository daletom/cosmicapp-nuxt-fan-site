<template>
<!-- This is an example for a logo that is animated. -->
  <video autoplay loop muted playsinline style="width: 200px; height: 60px">
    <source src="https://imgix.cosmicjs.com/bebd5ed0-f72e-11eb-a171-71d9db0ee496-lokilogo.gif?fm=mp4&w=200&h=60&fit=crop" type="video/mp4">
  </video>
</template>

<!-- This is an example for a logo that is not animated
<template>
  <ix-img
  src="https://imgix.cosmicjs.com/049dabb0-8e19-11ea-81c6-b3a804bfff46-cosmic-dark.png"
  width="200"
  height="60"
  fixed
  />
</template>

-->


<style>
.NuxtLogo {
  animation: 1s appear;
  margin: auto;
}

@keyframes appear {
  0% {
    opacity: 0;
  }
}
</style>
