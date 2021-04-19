<template>
  <div class="container">
    <div class="title">
      <h3>{{ list.title }}</h3>
      <a :href="list.more" style="text-decoration: none">
        <div class="see-all">
          <p>مشاهده همه</p>
          <font-awesome-icon :icon="['fas', 'user-secret']" />
        </div>
      </a>
    </div>
    <div class="list">
      <Product v-for="item in list.products" :key="item.id" :product="item" />
    </div>
  </div>
</template>

<script>
import Product from "./Product.vue";
export default {
  components: {
    Product,
  },
  props: {
    list: {
      type: Object,
    },
  },
};
</script>

<style scoped>
.container {
  padding: 1rem 2rem;
  background-image: url(https://statics.basalam.com/public/landing/photos/2101/EMfkuknEIQXeNbUYGxYocD9lRhLoDSeYjqJzVgGX.png);
  margin-top: 2rem;
}
.title {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}
.see-all {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 0rem 1rem;
  background: hsla(0, 0%, 100%, 0.5);
  border-radius: 50rem;
  color: #282828;
  cursor: pointer;
}
.list {
  display: flex;
  scroll-behavior: smooth;
  flex-direction: row;
  overflow-x: auto;
}
</style>
