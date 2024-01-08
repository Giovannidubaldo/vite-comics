<script>
export default {
    name: 'AppMain',
    data() {
        return {

        }
    }
}
</script>

<template lang="">
    <main>
        <div class="container">
            <div class="row">
                <h2>Content go here</h2>
            </div>
        </div>
    </main>
</template>

<style lang="scss">
@use '../styles/generals.scss';
@use '../styles/partials/variables' as *;

main {
    padding: 20px;
    color: $color_white
}
</style>