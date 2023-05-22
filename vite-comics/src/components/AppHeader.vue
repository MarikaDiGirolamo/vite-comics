<script>
export default {
    name: AppHeader,
    components: {

    },
    data() {
        return {

        }
    },
    methods() {

    },
    mounted() {

    }
}
</script>

<template>
    <div class="dc-navbar">
        <nav class="navbar nav-underline">
            <div class="container">
                <a class="navbar-brand" href="#">
                    <img src="../assets/img/dc-logo.png" alt="DC-LOGO" width="30" height="24">
                </a>
            </div>
            <ul class="nav justify-content-end">
                <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#">Character</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Comics</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Movies</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link"> Tv</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link">Games</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link"> Collectibles</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link"> Videos</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link"> Fans</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link"> News</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link">Shop</a>
                </li>
            </ul>
        </nav>
    </div>
</template>

<style scoped>
.dc-navbar {
    background-color: white;
    color: black;
}

.nav-link {
    text-decoration: none;
}

.nav-item:hover {
    color: #0282f9;
    cursor: pointer;
}
</style>