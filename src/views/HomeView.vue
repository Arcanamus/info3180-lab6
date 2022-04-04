<script>

export default {
    data() {
        return {
            message: "Hello World! Welcome to VueJS"
        };
    },
}
</script>

<template>
    <div class="container">
      <div class="text-center">
        <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />
        <h1>{{ message }}</h1>
      </div>
    </div>
</template>

<style>
h1 {
    padding-bottom: 20px;
}
.news__item {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  max-width: 300px;
  margin: auto;
  text-align: left;
  display: grid;
  width: 85%;
  height: 400px;
  background-color: white;
  justify-content: center;
  border-bottom: 5px solid green;
}

.news__item img {
  width: 300px;
  height: 150px;
}

.news__list {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-row-gap: 20px;
    grid-column-gap:5px;
}

.title {
    font-weight: bold;
    padding-left: 15px;
    padding-right: 15px;
}

.description {
    padding-left: 15px;
    padding-right: 15px;
    font-size: 12px;
}
</style>