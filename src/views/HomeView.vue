<template>
  <section class="hero">
    <div>
      <h1>This board is empty. Create a new column to get started.</h1>
      <button class="btn">+ Add New Column</button>
    </div>
  </section>
</template>

<style lang="scss">
@use "@/assets/scss/utils/variables.scss";
@use "@/assets/scss/utils/mixins.scss";
@use "@/assets/scss/components/button.scss";
.hero {
  height: 100vh;
  @include mixins.flexbox;
  padding: 0 41px;
  h1 {
    font-size: 18px;
    color: variables.$medium-grey;
    text-align: center;
    margin-bottom: 25px;
  }
  .btn {
    display: block;
    margin: 0 auto;
    width: 174px;
    height: 48px;
    font-size: 15px;
    font-weight: bold;
    color: white;
  }
}
</style>
