<template>
    <ul class="sidenav app-sidenav open">
      <router-link
      tag="li"
      active-class="active"
      to="/post"
      exact>
        <a href="#" class="waves-effect waves-orange pointer">Посты</a>
      </router-link>
      <router-link
      tag="li"
      active-class="active"
      to="/newpost"
      exact>
        <a href="#" class="waves-effect waves-orange pointer">Новый пост</a>
      </router-link>
      <li>
        <a href="#" class="waves-effect waves-orange pointer">Пользователи</a>
      </li>
    </ul>
</template>