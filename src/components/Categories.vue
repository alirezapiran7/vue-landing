<template>
  <div class="container">
    <div
      v-for="(category, index) in categories"
      :key="category.id"
      class="category-item"
      :style="{ marginTop: index % 2 === 0 ? -16 + 'rem' : 0 }"
    >
      <a href="{category.link}">
        <div class="disccount-badge">
          <span>تا</span>
          <span class="disccount">{{ category.discount }}</span>
        </div>
        <div class="img-container">
          <img
            src="https://statics.basalam.com/public/landing/photos/2101/9FIoTON600r4TvyhOYfRenB3mij8bq8DlibCRcNx.png"
            class="category-img"
          />
        </div>
      </a>
      <span class="category-title">{{ category.title }}</span>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      categories: [
        {
          id: 1,
          link:
            "https://basalam.com/search?q&namedTags=73201,74670,75107,74621,74840,77452,74051,75002,73202,77415,73202,75002,73302,73303,820512&type",
          image:
            "https://statics.basalam.com/public/landing/photos/2101/9FIoTON600r4TvyhOYfRenB3mij8bq8DlibCRcNx.png",
          title: "برنج و حبوبات",
          discount: "50",
        },
        {
          id: 2,
          link:
            "https://basalam.com/search?q&namedTags=73201,74670,75107,74621,74840,77452,74051,75002,73202,77415,73202,75002,73302,73303,820512&type",
          image:
            "https://statics.basalam.com/public/landing/photos/2101/9FIoTON600r4TvyhOYfRenB3mij8bq8DlibCRcNx.png",
          title: "برنج و حبوبات",
          discount: "50",
        },
        {
          id: 3,
          link:
            "https://basalam.com/search?q&namedTags=73201,74670,75107,74621,74840,77452,74051,75002,73202,77415,73202,75002,73302,73303,820512&type",
          image:
            "https://statics.basalam.com/public/landing/photos/2101/9FIoTON600r4TvyhOYfRenB3mij8bq8DlibCRcNx.png",
          title: "برنج و حبوبات",
          discount: "50",
        },
        {
          id: 4,
          link:
            "https://basalam.com/search?q&namedTags=73201,74670,75107,74621,74840,77452,74051,75002,73202,77415,73202,75002,73302,73303,820512&type",
          image:
            "https://statics.basalam.com/public/landing/photos/2101/9FIoTON600r4TvyhOYfRenB3mij8bq8DlibCRcNx.png",
          title: "برنج و حبوبات",
          discount: "50",
        },
        {
          id: 5,
          link:
            "https://basalam.com/search?q&namedTags=73201,74670,75107,74621,74840,77452,74051,75002,73202,77415,73202,75002,73302,73303,820512&type",
          image:
            "https://statics.basalam.com/public/landing/photos/2101/9FIoTON600r4TvyhOYfRenB3mij8bq8DlibCRcNx.png",
          title: "برنج و حبوبات",
          discount: "50",
        },
        {
          id: 6,
          link:
            "https://basalam.com/search?q&namedTags=73201,74670,75107,74621,74840,77452,74051,75002,73202,77415,73202,75002,73302,73303,820512&type",
          image:
            "https://statics.basalam.com/public/landing/photos/2101/9FIoTON600r4TvyhOYfRenB3mij8bq8DlibCRcNx.png",
          title: "برنج و حبوبات",
          discount: "50",
        },
      ],
    };
  },
};
</script>

<style scoped>
.container {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  margin-top: 20rem;
}
.category-item {
  display: flex;
  padding-right: 8px;
  padding-left: 8px;
  position: relative;
  justify-content: space-between;
  align-items: center;
  flex-direction: column;
  max-width: 13rem;
  max-height: 20.6rem;
  margin: auto;
  padding: 0.5rem 1.5rem 2rem;
  background: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTk0IiBoZWlnaHQ9IjE4MiIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48cGF0aCBkPSJNMTYxLjM5NCAxODEuMTI1SDMyLjMyMUMxNC42OTggMTgxLjEyNS40MSAxNjYuODEzLjQxIDE0OS4xNjJ2LTQ2Ljk5MUMuNDEgNjQuOSAyNi43ODQgMzIuOTM3IDYzLjMzOSAyNS45TDE5My4zMDUuODU0djE0OC4zMDhjMCAxNy42NTEtMTQuMjg5IDMxLjk2My0zMS45MTEgMzEuOTYzeiIgZmlsbD0iI0M4OTAwMCIvPjwvc3ZnPg==)
      bottom no-repeat,
    #fff;
  width: 100%;
  background-size: 100%;
  background-position-y: 100%;
  border-radius: 2.8rem;
  cursor: pointer;
  transition: all 0.3s linear;
}

.category-item a {
  display: flex;
}

.disccount-badge {
  position: absolute;
  top: -1rem;
  right: -1rem;
  width: 4rem;
  height: 4rem;
  background: url(data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iODYiIGhlaWdodD0iODYiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PHBhdGggZD0iTTQyLjY4NSA1LjA5Mkw0OS40OTcuMDE5bDQuNzgzIDYuODEyIDcuOTcxLTIuNjA5IDIuNjEgNy45NzIgOC4yNi0uMTQ1djguNDA2bDcuOTcyIDIuNjA5LTIuNjEgNy44MjYgNi44MTMgNC45MjgtNS4wNzMgNi42NjcgNS4wNzMgNi44MTItNi44MTIgNC43ODMgMi42MDkgNy45Ny03Ljk3MiAyLjYxdjguMjZoLTguMjZsLTIuNjEgNy45NzItNy45NzEtMi42MDktNC43ODMgNi44MTItNi44MTItNS4wNzItNi42NjcgNS4wNzItNC45MjctNi44MTItNy44MjcgMi42MS0yLjYwOS03Ljk3MkgxMi4yNWwuMTQ1LTguMjYxLTcuOTcxLTIuNjEgMi42MDktNy45N0wuMjIgNDkuMjk3bDUuMDcyLTYuODEyTC4yMiAzNS44MThsNi44MTItNC45MjgtMi42MS03LjgyNiA3Ljk3Mi0yLjYxLS4xNDUtOC40MDUgOC40MDYuMTQ1IDIuNjEtNy45NzIgNy44MjYgMi42MUwzNi4wMTguMDE4bDYuNjY3IDUuMDczeiIgZmlsbD0iI0M3NDUxQyIvPjwvc3ZnPg==)
    bottom no-repeat;
  background-size: cover;
  text-align: center;
  padding-top: 0.3rem;
}
.disccount-badge > span {
  display: block;
  color: #fff;
}
.disccount {
  position: relative;
  margin-top: -0.7rem;
  margin-left: -1rem;
  font-size: 1.7rem;
  font-weight: 700;
}
.category .img-container {
  height: 10rem;
}
.category-title {
  margin-top: -1.5rem;
  display: block;
  width: 100%;
  color: #fff;
  font-size: 1.5rem;
  text-align: right;
  font-weight: 500;
  letter-spacing: -1px;
}
</style>
