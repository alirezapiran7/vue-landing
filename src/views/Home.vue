<template>
  <div>
    <Banner />
    <Timer />
    <Products />
    <Categories />
    <Question />
  </div>
</template>

<script>
import Banner from "@/components/Banner.vue";
import Timer from "../components/Timer.vue";
import Categories from "../components/Categories.vue";
import Question from "../components/Question.vue";
import Products from "../components/Products.vue";

export default {
  components: { Banner, Timer, Categories, Question, Products },
};
</script>

<style scoped></style>
