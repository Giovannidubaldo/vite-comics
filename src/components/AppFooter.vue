<script>
export default {
    name: 'AppFooter',
}
</script>

<template lang="">
    <footer>

        <!-- Top Footer -->
        <div class="top-footer">
            <div class="container">
                <div class="footer-logo-dc d-flex">
                    <div class="menu">
                        <h3 class="text-uppercase">DC Comics</h3>
                        <ul class="list-unstyled">
                            <li>Characters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>Tv</li>
                            <li>Games</li>
                            <li>Collectibles</li>
                            <li>Videos</li>
                            <li>Fans</li>
                            <li>News</li>
                            <li>Shop</li>
                        </ul>
                        <h3 class="text-uppercase mt-3">shop</h3>
                        <ul class="list-unstyled">
                            <li>Shop DC</li>
                            <li>Shop DC collectibles</li>
                        </ul>
                    </div>
                    <div class="menu ms-5">
                        <h3 class="text-uppercase">dc</h3>
                        <ul class="list-unstyled">
                            <li>Terms Of Use</li>
                            <li>Privacy Police</li>
                            <li>Ad Choices</li>
                            <li>Advertising</li>
                            <li>Jobs</li>
                            <li>Jobs</li>
                            <li>Jobs</li>
                            <li>Jobs</li>
                            <li>Jobs</li>
                            <li>Jobs</li>
                            <li>Jobs</li>
                        </ul>
                    </div>
                    <div class="menu ms-5">
                        <h3 class="text-uppercase">sites</h3>
                        <ul class="list-unstyled">
                            <li>DC</li>
                            <li>MAD Magazine</li>
                            <li>DC Kids</li>
                            <li>DC Universe</li>
                            <li>DC Power Visa</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>

        <!-- Bottom footer -->
        <div class="bottom-footer">
            <div class="container">
                <div class="row">
                    <div class="d-flex justify-content-between align-items-center">
                        <button>sign-up now!</button>
                        <a href="#">follow us</a>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;
@use '../styles/generals.scss' as *;

.top-footer {
    background-image: url('../assets/img/footer-bg.jpg');

    .footer-logo-dc {
        background-image: url('../assets/img/dc-logo-bg.png');
        background-position: right;
        background-repeat: no-repeat;

        .menu {
            padding: 50px 0;

            h3 {
                color: $color_white;
            }

            ul {
                margin: 0;

                li {
                    padding: 0;
                    color: grey;
                }
            }
        }
    }
}

.bottom-footer {
    background-color: rgb(77, 77, 77);
    padding: 30px 0;

    button {
        text-transform: uppercase;
        padding: 10px;
        color: $color_white;
        background-color: rgb(77, 77, 77);
        border: 1px solid $color_blue;
    }

    a {
        text-transform: uppercase;
        text-decoration: none;
        color: $color_blue;
    }
}
</style>