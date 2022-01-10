<template>
  <div class="card">
      <div>
          <img class="card__image" :src="`http://placeimg.com/300/200/${info.id}`" :alt="info.title">
      </div>
      <div class="card__body">
          <h3>{{info.title}}</h3>
          <p>{{info.body}}</p>
      </div>
  </div>
</template>

<script>
export default {
    name: 'Card',
    props: {
        info: Object
    }
}
</script>

<style lang="scss" scoped>
.card {
    color: #333;
    border-radius: 10px;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    height: 100%;

    &__image {
        width: 100%;
    }

    &__body {
        padding: 10px;
    }
}
</style>