<template>
  <div class="banner">
    <div>
      <img
        src="https://statics.basalam.com/public/landing/photos/2101/RyntqgYT6hfFiUtZ3Sgxa2qyB78yYmgA5Bfa8Hz8.png"
      />
    </div>
    <div class="layer">
      <img
        src="https://statics.basalam.com/public/landing/photos/2101/PBkDYinkq1QQPjO2ojzAdGTdkLSfW4foCeJjPs20.png"
      />
    </div>
    <div class="layer">
      <img
        src="https://statics.basalam.com/public/landing/photos/2101/Ks6z45sHvu8VJJRDk808oxiyicxrjmvQtsFOub1R.png"
      />
    </div>
    <div class="info">
      <h4>روز بیشترین تخفیف‌ها</h4>
      <p>
        . فقط 24 ساعت فرصت دارید تا با مناسب‌ترین قیمت‌ها، محصولات موردنیاز خود
        را از باسلام بخرید
      </p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.banner {
  position: relative;
  width: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  overflow: hidden;
  background: url(https://statics.basalam.com/public/landing/photos/2101/18WysfNq6XCxWXUSYL3qpfidPGO0mIyOJimOYpSe.jpeg)
      50% no-repeat,
    #ffc624;
  background-size: cover;
}
.layer {
  position: absolute;
}
img {
  width: 100%;
}
h4 {
  color: #9c6716;
  font-size: 1.6rem;
}
.info {
  display: flex;
  width: 100%;
  align-content: center;
  flex-direction: column;
  padding-bottom: 60px;
  text-align: center;
  background: #ffc624;
  line-height: 1rem;
  z-index: 2;
  background: linear-gradient(0deg, #ffc624 60%, rgba(255, 198, 36, 0));
  margin-top: -16rem;
}
p {
  text-align: "center";
  direction: ltr;
  text-justify: auto;
}
/* @media (max-width: 500px) {
  .banner {
    width: 500px;
  }
} */
</style>
