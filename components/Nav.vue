<template>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark padding">
        <a class="navbar-brand" href="https://www.gob.mx/" target="_blank"> <img src="@/assets/images/Gobierno.png" width="110" height="40"> </a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse ml-auto" id="navbarSupportedContent">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <a href="https://www.gob.mx/tramites" class="nav-link" target="_blank">Tramites <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item active">
                    <a href="https://www.gob.mx/gobierno" class="nav-link" target="_blank">Gobierno <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item active">
                    <a href="https://www.gob.mx/busqueda" class="nav-link" target="_blank">🔎</a> <span class="sr-only">(current)</span>
                </li>
            </ul>
        </div>
    </nav>
</template>

<script>
    export default {

    }         

</script>

<style scoped>
 .navbar.navbar-dark.bg-dark{
    background-color: rgb(11, 35, 30)!important;
    width: 100%;
    position: fixed;
    top: 20px;
    z-index: 100;
 }
    .nav-left {
        margin-left: auto;
    }

    .brand img {
        width: 75px;
        height: 100rem;
    }
</style>