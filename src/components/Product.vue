<template>
  <div class="contianer">
    <a :href="product.link">
      <img :src="product.image" :alt="product.title" />
    </a>
    <a href="product.link">
      <p class="title">{{ product.title }}</p>
    </a>
    <a href="product.seller">
      <p class="seller">{{ product.seller }}</p>
    </a>

    <div class="comment">
      <span class="seller">
        <span style="color: #000; font-size: 0.8rem"> {{ product.rate }}</span>
        ({{ product.comments }} نظر)
      </span>
      <span class="discount">{{ product.discount }}%</span>
    </div>
    <div class="comment">
      <div class="add">+</div>
      <p class="price">{{ product.price }} تومان</p>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    product: {
      type: Object,
    },
  },
};
</script>

<style scoped>
.contianer {
  position: relative;
  overflow: hidden;
  background-color: #fff;
  border: 1px solid #e9ecef;
  box-sizing: border-box;
  border-radius: 12px;
  min-width: 12rem;
  width: 220px;
  padding: 0.2rem;
  margin-left: 15px;
}
a {
  text-decoration: none;
}
.title {
  font-size: 0.7rem;
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
  color: #000;
}
.seller {
  font-size: 0.6rem;
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
  color: #343a40;
}
img {
  width: 202;
  height: 220px;
}
.discount {
  color: #dc3755;
  font-size: 0.6rem;
  line-height: 1.1rem;
  border-radius: 4px;
  padding: 0.125rem 0.25rem;
  background-color: #fcecef;
}
.comment {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}
.price {
  text-align: left;
}
.add {
  color: #dc3755;
  border-radius: 4px;
  width: 25px;
  height: 25px;
  background-color: #fcecef;
  cursor: pointer;
  text-align: center;
}
</style>
