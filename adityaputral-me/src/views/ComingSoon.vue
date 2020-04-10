<template>
  <div class="container">
    <div class="wrapper">
      <img class="logo" alt="Logo" src="../assets/logo.png" />
      <h1 class="container__title">Coming Soon!</h1>
      <div class="container__anchor">
        <a
          class="container__subtext"
          href="https://www.instagram.com/adityaputral"
          >@adityaputral</a
        >

        <a
          class="container__subtext container__subtext--shop"
          href="http://www.shop.spasium.com/artist/aditya-putra-l."
          >Shop my artworks</a
        >
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.container {
  height: 100vh;

  background: linear-gradient(to right, #ece9e6, #ffffff);
  background-image: url("./../assets/images/bg.png");
  object-fit: cover;
  background-repeat: no-repeat;

  .wrapper {
    position: relative;
    width: 100%;
    max-width: 1440px;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    margin: 0 auto;

    @media (max-width: 1440px) {
      max-width: 1200px;
    }
  }

  .logo {
    position: absolute;
    top: 15px;
    left: 15px;
    max-width: 75px;
  }

  &__anchor {
    display: flex;
    justify-content: center;
    align-items: center;
  }

  &__title {
    font-family: CambayRegular, "sans-serif";
    font-size: 80px;
  }

  &__subtext {
    font-family: CambayRegular, "sans-serif";
    text-decoration: none;
    color: #2b7a78;
    transition: color 0.4s ease;

    &--shop.container__subtext {
      margin-left: 40px;
      border: 1px solid #2b7a78;
      border-radius: 5px;
      padding: 20px;
      transition: all 0.4s ease;

      &:hover {
        background-color: #2b7a78;
        color: #feffff;
      }
    }

    &:hover {
      color: #3aafa9;
    }
  }
}
</style>
