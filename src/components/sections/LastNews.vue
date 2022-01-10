<template>
  <section id="ultime-news" class="last-news bg-primary-color">
    <div class="container">
        <h2>Ultime News</h2>
        <div class="row">
            <div class="col-3 mb-3" v-for="(post, index) in lastPosts" :key="index">
                <Card :info="post"/>
            </div>
        </div>
    </div>
  </section>
</template>

<script>
import axios from 'axios';
import Card from '../elements/Card.vue';

export default {
    name: 'LastNews',
    components: {
        Card
    },
    data() {
        return {
            posts: []
        }
    },
    created() {
        axios.get('https://jsonplaceholder.typicode.com/posts')
        .then( (response) => {
            this.posts = response.data;
        });
    },
    computed: {
        lastPosts() {
            return this.posts.slice(0,8);
        },
        bestPost() {
            return this.posts[Math.floor(Math.random() * 101)];
        }
    }
}
</script>

<style lang="scss" scoped>
.last-news {
    transform: skewY(-3deg);

    > * {
        transform: skewY(3deg);
    }
}
</style>