<template>
  <div class="container">
    <ProductList v-for="item in list" :key="item.id" :list="item" />
  </div>
</template>

<script>
import ProductList from "@/components/ProductList.vue";
export default {
  components: {
    ProductList,
  },
  data() {
    return {
      list: [
        {
          id: "1",
          title: "موادغذایی",
          more: "https://basalam.com/explore/product-all-users-foodstuffs1111",
          backgroundImage:
            "https://statics.basalam.com/public/landing/photos/2101/EMfkuknEIQXeNbUYGxYocD9lRhLoDSeYjqJzVgGX.png",
          products: [
            {
              id: "1",
              title:
                "آلوچه اعلا آذربایجان 2 کیلویی (سایر محصولات ما را هم ببینید و از تخفیف های موجود بهره ببرید)",
              image:
                "https://statics.basalam.com/public/users/L7gjX/2101/6HRxSTMGVPoNVKut2DXg6l1zdfpRpXzQZ7hZq21n.jpeg_256X256X70.jpeg",
              seller: "فروشگاه و خشکبار یوسف",
              price: 200000,
              discount: 31,
              rate: 2.8,
              comments: 48,
              link: "https://basalam.com/yoosof/product/209441",
            },
            {
              id: "2",
              title:
                "آلوچه اعلا آذربایجان 2 کیلویی (سایر محصولات ما را هم ببینید و از تخفیف های موجود بهره ببرید)",
              image:
                "https://statics.basalam.com/public/users/L7gjX/2101/6HRxSTMGVPoNVKut2DXg6l1zdfpRpXzQZ7hZq21n.jpeg_256X256X70.jpeg",
              seller: "فروشگاه و خشکبار یوسف",
              price: 200000,
              discount: 31,
              rate: 2.8,
              comments: 48,
              link: "https://basalam.com/yoosof/product/209441",
            },
            {
              id: "3",
              title:
                "آلوچه اعلا آذربایجان 2 کیلویی (سایر محصولات ما را هم ببینید و از تخفیف های موجود بهره ببرید)",
              image:
                "https://statics.basalam.com/public/users/L7gjX/2101/6HRxSTMGVPoNVKut2DXg6l1zdfpRpXzQZ7hZq21n.jpeg_256X256X70.jpeg",
              seller: "فروشگاه و خشکبار یوسف",
              price: 200000,
              discount: 31,
              rate: 2.8,
              comments: 48,
              link: "https://basalam.com/yoosof/product/209441",
            },
            {
              id: "4",
              title:
                "آلوچه اعلا آذربایجان 2 کیلویی (سایر محصولات ما را هم ببینید و از تخفیف های موجود بهره ببرید)",
              image:
                "https://statics.basalam.com/public/users/L7gjX/2101/6HRxSTMGVPoNVKut2DXg6l1zdfpRpXzQZ7hZq21n.jpeg_256X256X70.jpeg",
              seller: "فروشگاه و خشکبار یوسف",
              price: 200000,
              discount: 31,
              rate: 2.8,
              comments: 48,
              link: "https://basalam.com/yoosof/product/209441",
            },
            {
              id: "5",
              title:
                "آلوچه اعلا آذربایجان 2 کیلویی (سایر محصولات ما را هم ببینید و از تخفیف های موجود بهره ببرید)",
              image:
                "https://statics.basalam.com/public/users/L7gjX/2101/6HRxSTMGVPoNVKut2DXg6l1zdfpRpXzQZ7hZq21n.jpeg_256X256X70.jpeg",
              seller: "فروشگاه و خشکبار یوسف",
              price: 200000,
              discount: 31,
              rate: 2.8,
              comments: 48,
              link: "https://basalam.com/yoosof/product/209441",
            },
            {
              id: "6",
              title:
                "آلوچه اعلا آذربایجان 2 کیلویی (سایر محصولات ما را هم ببینید و از تخفیف های موجود بهره ببرید)",
              image:
                "https://statics.basalam.com/public/users/L7gjX/2101/6HRxSTMGVPoNVKut2DXg6l1zdfpRpXzQZ7hZq21n.jpeg_256X256X70.jpeg",
              seller: "فروشگاه و خشکبار یوسف",
              price: 200000,
              discount: 31,
              rate: 2.8,
              comments: 48,
              link: "https://basalam.com/yoosof/product/209441",
            },
            {
              id: "7",
              title:
                "آلوچه اعلا آذربایجان 2 کیلویی (سایر محصولات ما را هم ببینید و از تخفیف های موجود بهره ببرید)",
              image:
                "https://statics.basalam.com/public/users/L7gjX/2101/6HRxSTMGVPoNVKut2DXg6l1zdfpRpXzQZ7hZq21n.jpeg_256X256X70.jpeg",
              seller: "فروشگاه و خشکبار یوسف",
              price: 200000,
              discount: 31,
              rate: 2.8,
              comments: 48,
              link: "https://basalam.com/yoosof/product/209441",
            },
          ],
        },
        {
          id: "2",
          title: "شاید بپسندید",
          more:
            "https://basalam.com/explore/product-all-users-you-might-like-it1111",
          backgroundImage:
            "https://statics.basalam.com/public/landing/photos/2101/EMfkuknEIQXeNbUYGxYocD9lRhLoDSeYjqJzVgGX.png",
          products: [
            {
              id: "1",
              title:
                "آلوچه اعلا آذربایجان 2 کیلویی (سایر محصولات ما را هم ببینید و از تخفیف های موجود بهره ببرید)",
              image:
                "https://statics.basalam.com/public/users/L7gjX/2101/6HRxSTMGVPoNVKut2DXg6l1zdfpRpXzQZ7hZq21n.jpeg_256X256X70.jpeg",
              seller: "فروشگاه و خشکبار یوسف",
              price: 200000,
              discount: 31,
              rate: 2.8,
              comments: 48,
              link: "https://basalam.com/yoosof/product/209441",
            },
            {
              id: "1",
              title:
                "آلوچه اعلا آذربایجان 2 کیلویی (سایر محصولات ما را هم ببینید و از تخفیف های موجود بهره ببرید)",
              image:
                "https://statics.basalam.com/public/users/L7gjX/2101/6HRxSTMGVPoNVKut2DXg6l1zdfpRpXzQZ7hZq21n.jpeg_256X256X70.jpeg",
              seller: "فروشگاه و خشکبار یوسف",
              price: 200000,
              discount: 31,
              rate: 2.8,
              comments: 48,
              link: "https://basalam.com/yoosof/product/209441",
            },
            {
              id: "1",
              title:
                "آلوچه اعلا آذربایجان 2 کیلویی (سایر محصولات ما را هم ببینید و از تخفیف های موجود بهره ببرید)",
              image:
                "https://statics.basalam.com/public/users/L7gjX/2101/6HRxSTMGVPoNVKut2DXg6l1zdfpRpXzQZ7hZq21n.jpeg_256X256X70.jpeg",
              seller: "فروشگاه و خشکبار یوسف",
              price: 200000,
              discount: 31,
              rate: 2.8,
              comments: 48,
              link: "https://basalam.com/yoosof/product/209441",
            },
          ],
        },
      ],
    };
  },
};
</script>
<style scoped>
.container {
  display: flex;
  flex-direction: column;
}
</style>
