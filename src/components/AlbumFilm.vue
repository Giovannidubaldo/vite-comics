<script>
export default {
    name: 'AlbumFilm',
    props: {
        films: Object
    }
}
</script>

<template lang="">
    <div class="album-film">
            <img :src="films.thumb" alt="">
            <h6 class="text-uppercase mt-3">{{films.series}}</h6>
    </div>
</template>

<style lang="scss" scoped>
.album-film {
    width: calc(100% / 6 - 20px);
    margin: 10px;
}
</style>