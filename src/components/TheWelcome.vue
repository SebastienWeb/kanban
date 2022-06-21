<template>
  <header>
    <img src="../assets/images/logo-light.svg" alt="Logo de Kanban" />
    <div class="containerNav">
      <button class="btn">+</button>
      <div class="container">
        <div></div>
        <div></div>
        <div></div>
      </div>
    </div>
  </header>
</template>
<style lang="scss" scoped>
@use "@/assets/scss/utils/variables.scss";
@use "@/assets/scss/components/button.scss";
header {
  background-color: variables.$dark-grey;
  padding: 20px 16px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  .containerNav {
    display: flex;
    align-items: center;
    & .btn {
      width: 48px;
      height: 32px;
      margin-right: 25px;
    }
    .container {
      div {
        width: 3.69px;
        height: 3.69px;
        background-color: variables.$medium-grey;
        border-radius: 50%;
        &:nth-child(2) {
          margin: 2px 0;
        }
      }
    }
  }
}
</style>
