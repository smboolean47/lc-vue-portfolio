<template>
  <nav class="nav-bar">
      <ul class="nav-bar__list">
        <li class="nav-bar__item">
            <a href="#chi-siamo">Chi Sono</a>
        </li>
        <li class="nav-bar__item">
            <a href="#ultime-news">Ultime News</a>
        </li>
        <li class="nav-bar__item">
            <a href="#contatti">Contatti</a>
        </li>
      </ul>
  </nav>
</template>

<script>
export default {
    name: 'NavBar',
}
</script>

<style lang="scss" scoped>
.nav-bar {
    font-size: 20px;
    // .nav-bar__list
    &__list {
        display: flex;
        list-style: none;
        align-items: center;
        justify-content: flex-end;
        margin-bottom: 0;
    }
    // .nav-bar__item
    &__item {
        margin-left: 20px;

        a {
            color: inherit;
            text-decoration: none;
        }
    }
}
</style>