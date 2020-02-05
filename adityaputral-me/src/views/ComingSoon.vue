<template>
  <div class="container">
    <h1 class="container__title">Coming Soon!</h1>
    <a class="container__subtext" href="https://www.instagram.com/adityaputral"
      >@adityaputral</a
    >
  </div>
</template>

<style lang="scss" scoped>
.container {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  background: linear-gradient(to right, #ece9e6, #ffffff);
  background-image: url("./../assets/images/bg.png");
  object-fit: cover;
  background-repeat: no-repeat;

  &__title {
    font-family: CambayRegular, "sans-serif";
    font-size: 80px;
  }

  &__subtext {
    font-family: CambayRegular, "sans-serif";
    text-decoration: none;
    color: #2b7a78;
    transition: color 0.3s ease;

    &:hover {
      color: #3aafa9;
    }
  }
}
</style>
