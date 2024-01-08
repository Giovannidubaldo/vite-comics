<script>
export default {
    name: 'AppHeader',
    data() {
        return {
            menu: [
                {
                    name: 'characters',
                    url: '#',
                    current: false
                },
                {
                    name: 'comics',
                    url: '#',
                    current: false
                },
                {
                    name: 'movies',
                    url: '#',
                    current: false
                },
                {
                    name: 'tv',
                    url: '#',
                    current: false
                },
                {
                    name: 'games',
                    url: '#',
                    current: false
                },
                {
                    name: 'collectibles',
                    url: '#',
                    current: false
                },
                {
                    name: 'videos',
                    url: '#',
                    current: false
                },
                {
                    name: 'fans',
                    url: '#',
                    current: false
                },
                {
                    name: 'news',
                    url: '#',
                    current: false
                },
                {
                    name: 'shop',
                    url: '#',
                    current: false
                },
            ]
        }
    }
}
</script>
<template lang="">
    <header>
        <div class="container">
            <div class="row">
                <div class="d-flex justify-content-between align-items-center p-3">
                    <img src="../assets/img/dc-logo.png" alt="">
                    <ul class="list-unstyled d-flex">
                        <li v-for="(menu, index) in menu" :key="index" class="p-2 text-uppercase">
                            <a :class="menu.current ? 'active' : ''" href="menu.url">
                                {{menu.name}}
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </header>
</template>
<style lang="scss">
@use '../styles/partials/variables' as *;

li a {
    text-decoration: none;
    color: black;

    &:active,
    &:hover {
        color: $color_blue;
        border-bottom: 1px solid $color_blue;
    }
}
</style>