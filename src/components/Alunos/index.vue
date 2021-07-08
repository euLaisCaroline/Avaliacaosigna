<template>
  <div class="container">
    <div class="container__content">
      <div class="container__content__list">
        <h1>Lista de Alunos</h1>
        <v-btn class="container__content__button" color="primary">Novo </v-btn>
      </div>

      <table>
        <thead>
          <tr>
            <th class="container__content__text">
              <!-- <input type="checkbox" /> -->
            </th>
            <th class="container__content__text">Nome</th>
            <th class="container__content__text">Email</th>
            <th class="container__content__text">Skills</th>
            <th class="container__content__text">Adicionado em:</th>
          </tr>
        </thead>

        <tbody>
          <tr class="container__content__table">
            <td>
              <img
                src="@/assets/image.png"
                class="container__content__table__img"
              />
              <span>Lindsey Stroud</span>
            </td>
            <td>
              <h2>nicci.troiani@gmail.com</h2>
            </td>
            <td>
              <button class="container__content__table__button">HTML</button>
              <button class="container__content__table__button">VUE</button>
              <button class="container__content__table__button">REACT</button>
              <button class="container__content__table__button">ANGULAR</button>
            </td>
            <td><h4>5 Minutes ago</h4></td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.container {
  display: flex;
  background: #e5e5e5;
  &__content {
    width: 100%;
    max-width: 1140px;

    h1 {
      font-family: Poppins;
      font-weight: 500;
      font-size: 20px;
      color: #109cf1;
    }
    &__list {
      display: flex;
      justify-content: space-between;
    }
    &__text {
      font-family: Poppins;
      font-weight: 500;
      font-size: 13px;
      font-style: normal;
      color: #98a5b6;
      // margin-right: 50px;
    }
    &__table {
      background: #fff;
      // margin-bottom: 1px solid #707683;
      &__img {
        background: #fff;
        border-radius: 50px;
        margin-left: 128px;
      }
      span {
        background: #fff;
        font-family: Poppins;
        font-size: 15px;

        margin-left: 30px;
        color: #323c47;
      }
      h2 {
        font-family: Poppins;
        font-size: 13px;
        font-weight: 400;
        color: #707683;
        margin-left: 120px;
      }
      &__button {
        height: 35px;
        width: 65px;
        font-size: 13px;
        margin-left: 15px;
        border: 1px solid #109cf1;
        border-radius: 5px;
        color: #109cf1;
      }
      h4 {
        font-family: Poppins;
        font-size: 13px;
        font-weight: 400;
        color: #707683;
        // margin-left: 30px;
      }
    }
    table {
      background: #fff;
    }
    &__check {
      // width: 150px;
      // margin-left: 70px;
    }
  }
}
</style>
