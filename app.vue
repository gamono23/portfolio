<template>
  <div>
    <NuxtLayout></NuxtLayout>
    <NuxtPage />
    <img src="http://ghchart.rshah.org/gamono23" alt="gamono23's Github chart" class="chart"/>
    <about></about>
    <projects></projects>
  </div>
</template>
<style>
@font-face {
  font-family: "San Francisco";
  font-weight: 400;
  src: url("https://applesocial.s3.amazonaws.com/assets/styles/fonts/sanfrancisco/sanfranciscodisplay-regular-webfont.woff");
}
.chart{
  display: flex;
  width: 50vw;
  margin-left: 25%;
  justify-content: center;
  align-items: center;
}
body{
  background-color: rgb(255, 209, 218);
}
</style>