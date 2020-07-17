<template>
    <div>
  <div class="page-title">
    <h3>Новый пост</h3>
  </div>

  <form class="form">
    <div class="input-field">
      <input
          id="amount"
          type="text"
      >
      <label for="amount">Введите имя</label>
    </div>

    <div class="input-field">
      <input
          id="description"
          type="text"
      >
      <label for="description">Введите заголовок</label>
    </div>

    <div class="input-field">
      <input
          id="description"
          type="text"
      >
      <label for="description">Введите текс</label>
    </div>

    <button class="btn waves-effect waves-light" type="submit">
      Создать
      <i class="material-icons right">send</i>
    </button>
  </form>
</div>
</template>