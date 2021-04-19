<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style>
@font-face {
  font-family: "IRANSans";
  src: local("IRANSans"), url(./assets/fonts/IRANSans.ttf) format("truetype");
}
body {
  height: 100%;
  margin: 0;
  font-family: IRANSans, sans-serif;
  font-size: 1rem;
  font-weight: 400;
  text-align: right;
  background-color: #ffc624;
  direction: rtl;
}
</style>
