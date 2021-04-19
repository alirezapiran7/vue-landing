<template>
  <div class="container">
    <div class="timer">
      <div class="clock">
        <span class="title">هر ساعت یک تخفیف</span>
        <span class="counters">0</span>
        <span class="dot">:</span>
        <span class="counters">0</span>
      </div>
      <div
        class="swiper-wrapper"
        style="
          transition: all 0ms ease 0s;
          transform: translate3d(0px, 0px, 0px);
        "
      >
        <div class="item"></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.timer {
  width: 800px;
  max-width: 100%;
  align-items: center;
  text-align: center;
}
.clock {
  display: inline-block;
  width: 10rem;
  border-radius: 1rem;
  border: 3px solid #dc3855;
  background: #333;
  text-align: center;
  color: #fff;
}
.clock .title {
  margin: 0.5rem;
  display: block;
  color: #ffc624;
  font-size: 0.8rem;
}
.counters {
  display: inline-block;
  padding: 0.6rem 0;
  width: 4rem;
  border-top: 3px solid #dc3855;
  border-bottom: 3px solid #dc3855;
  background: #333;
  border-radius: 1rem;
  font-size: 1.7rem;
  font-weight: bolder;
  margin-bottom: -0.6rem;
}
.dot {
  text-align: center;
  font-size: 2rem;
  width: 2rem;
  color: #fff;
}
.swiper-wrapper {
  position: relative;
  width: 100%;
  height: 100%;
  z-index: 1;
  display: flex;
  transition-property: transform;
  box-sizing: content-box;
}
.item {
  width: 230.333px;
  height: 230px;
  margin-left: 15px;
}
</style>
