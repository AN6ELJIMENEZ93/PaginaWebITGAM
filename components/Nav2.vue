<template>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark padding">
        <a class="navbar-brand"> <img src="@/assets/images/banner.png" width="800" height="150"> </a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse ml-auto" id="navbarSupportedContent">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <a href="https://login.microsoftonline.com/common/oauth2/authorize?client_id=4345a7b9-9a63-4910-a426-35363201d503&response_mode=form_post&response_type=code+id_token&scope=openid+profile&state=OpenIdConnect.AuthenticationProperties%3dDApM12-M8FcvM3T-x7Tuh9Dl44YvA0qLEIGpUlrbcMhCRsJ6ywIIgjX93vQFrXtYhbzxBHNcvPsfsNNFeAi-Ia-cEZnPbL07Zxf4_GUnQ93p5PK2yfz2sTWylDsfqF4lrLkY9kXsqLyIv9BYMNrU2A&nonce=637109879343170419.MjY5YzI4NmUtZmY0Yi00YjFiLWFjNmYtOTA1ZGYzOGY1MTZhY2M4ZWZkYmUtMGM4ZC00ZjNhLTljNzAtYzlkN2E3M2ZjNzg0&redirect_uri=https%3a%2f%2fwww.office.com%2f&ui_locales=es-ES&mkt=es-ES&client-request-id=44a9d438-1e22-4267-a3ad-db5a2fa0cb29&sso_reload=true" class="nav-link" target="_blank"> <img src="@/assets/images/correo-icono.png"> <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item active">
                    <a href="@/assets/documents/Calendario Escolar Agosto-diciembre 2023.pdf" class="nav-link" target="_blank"> <img src="@/assets/images/calendario-icono.png"> <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item active">
                    <a class="btn btn-outline-info" href="https://docs.google.com/forms/d/e/1FAIpQLSf9O2d-IwxCyBMMigDTcGS6r-27LMCj1I9VOfImrq2pnr5aJg/viewform" target="_blank">Consulta Aqui</a>
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
    background-color: rgb(255, 255, 255)!important;
 }
    .nav-left {
        margin-left: auto;
    }
</style>