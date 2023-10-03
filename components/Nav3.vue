<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark padding">
  
      <b-navbar-nav class="">
        <NuxtLink to="" class="nav-link">🏠 <span class="sr-only">(current)</span></NuxtLink>
        <b-nav-item-dropdown text="🏢 Nuestro campus" right> 
          <b-dropdown-item><NuxtLink to="/NuestroCampus/Historia">Historia</NuxtLink></b-dropdown-item>
          <b-dropdown-item><NuxtLink to="/NuestroCampus/MisionVisionValores">MisionVisionValores</NuxtLink></b-dropdown-item>
          <b-dropdown-item><NuxtLink to="/NuestroCampus/EstructuraOrganizacional">Estructura Organizacional</NuxtLink></b-dropdown-item>
          <b-dropdown-item><NuxtLink to="@/cliente/assets/images/NuestroCampus/Directorio 2023.webp">Directorio</NuxtLink></b-dropdown-item>
          <b-dropdown-item><NuxtLink to="/NuestroCampus/AvisoPrivacidad" target="blank">Aviso de Privacidad TECNM</NuxtLink></b-dropdown-item>
          <b-dropdown-item><NuxtLink to="/NuestroCampus/MarcoNormativo">Marco Normativo</NuxtLink></b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="🏢 Departamentos"  right>
          <b-dropdown-item><NuxtLink to="/Departamentos/SubdireccionAcademica">Subdirección Academica</NuxtLink></b-dropdown-item>
          <b-dropdown-item><NuxtLink to="/Departamentos/PRODEP">PRODEP</NuxtLink> </b-dropdown-item>
          <b-dropdown-item><NuxtLink to="/Departamentos/SubdireccionServiciosAdministrativos">Subdirección de Servicios Administrativos</NuxtLink></b-dropdown-item>
          <b-dropdown-item><NuxtLink to="/Departamentos/SubdireccionPlaneacionVinculacion">Subdirección de Planeación y Vinculación</NuxtLink></b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="🏢 Oferta Educativa"  right>
          <b-dropdown-item><NuxtLink to="/OfertaEducativa/ITICS">Ingeniería en Tecnologías de la Información y Comunicación</NuxtLink></b-dropdown-item>
          <b-dropdown-item><NuxtLink to="/OfertaEducativa/IGEM">Ingeniería en Gestión Empresarial</NuxtLink></b-dropdown-item>
          <b-dropdown-item><NuxtLink to="/OfertaEducativa/ILOG">Ingeniería en Logistica</NuxtLink></b-dropdown-item>
          <b-dropdown-item><NuxtLink to="/OfertaEducativa/IAMB">Ingeniería Ambiental</NuxtLink></b-dropdown-item>
          <b-dropdown-item><NuxtLink to="/OfertaEducativa/IIND">Ingeniería Industial</NuxtLink></b-dropdown-item>
          <b-dropdown-item><NuxtLink to="/OfertaEducativa/IFER">Ingeniería Ferroviaria</NuxtLink></b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="👤 Aspirantes"  right>
          <b-dropdown-item href="/Aspirantes/ConvocatoriaNuevoIngreso" target="blank">Convocatoria Nuevo Ingreso</b-dropdown-item>
          <b-dropdown-item href="/Aspirantes/Cronograma" target="blank">Cronograma</b-dropdown-item>
          <b-dropdown-item href="/Aspirantes/GuiaRegistro" target="blank">Guia de Registro</b-dropdown-item>
          <b-dropdown-item href="http://187.188.185.18:8010/cgi-bin/sie.pl?Opc=PINDEXASPIRANTE&psie=intertec&dummy=0" target="blank">SIE</b-dropdown-item>
          <b-dropdown-item><NuxtLink to="/Aspirantes/FormatosNuevoIngreso">Formatos Nuevo Ingreso</NuxtLink></b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="🙍‍♂️ Estudiantes"  right>
          <b-dropdown-item href="http://187.188.185.18:8010/cgi-bin/sie.pl?Opc=PINDEXESTUDIANTE&psie=intertec&dummy=0" target="blank">SIE</b-dropdown-item>
          <b-dropdown-item href="/Estudiantes/Reinscripcion">Reinscripción</b-dropdown-item>
          <b-dropdown-item href="/Estudiantes/ActividadesComplementarias">Actividades Complementarias</b-dropdown-item>
          <b-dropdown-item href="/Estudiantes/ServicioSocial">Servicio Social</b-dropdown-item>
          <b-dropdown-item href="/Estudiantes/ResidenciasProfesionales">Residencias Profesionales</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="👨‍🎓 Egresados"  right>
          <b-dropdown-item href="http://187.188.185.18:8010/cgi-bin/sie.pl?Opc=PINDEXESTUDIANTE&psie=intertec&dummy=0" target="blank">SIE</b-dropdown-item>
          <b-dropdown-item href="/Egresados/Titulacion">Titulación</b-dropdown-item>
          <b-dropdown-item href="/Egresados/SeguimientoEgresados">Seguimiento de Egresados</b-dropdown-item>
          <b-dropdown-item href="https://docs.google.com/forms/d/e/1FAIpQLSc_Xpq5XvSq9YI1arceYkwPgN6nE21SSf_dyaUuBJMQGOXd9Q/viewform">Bolsa de Trabajo</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="👨‍🏫 Docentes"  right>
          <b-dropdown-item href="/Docentes/Convocatorias">Convocatoria</b-dropdown-item>
          <b-dropdown-item href="http://187.188.185.18:8010/cgi-bin/sie.pl?Opc=PINDEXDOCENTE&psie=intertec&dummy=0">SIE</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="👤 Vinculación" right>
          <b-dropdown-item href="/Vinculacion/Contacto">Contacto</b-dropdown-item>
          <b-dropdown-item href="#">Consejo de Vinculación</b-dropdown-item>
          <b-dropdown-item href="#">Visitas de Empresas</b-dropdown-item>
          <b-dropdown-item href="#">Widget de OCC</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="👤 C.L.E"  right>
          <b-dropdown-item a href="#">Niveles</b-dropdown-item>
          <b-dropdown-item href="/CLE/Convocatorias">Convocatorias</b-dropdown-item>
          <b-dropdown-item href="#">Acceso</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="📚 Biblioteca"  right>
          <b-dropdown-item href="https://elibro.net/es/lc/gamadero/login_usuario/?next=/es/lc/gamadero/inicio/" target="blank">e-Libro Biblioteca Digital</b-dropdown-item>
          <b-dropdown-item href="#">Video e-Libro</b-dropdown-item>
        </b-nav-item-dropdown>
        <b-nav-item-dropdown text="💳 Pago de Servicios"  right>
          <b-dropdown-item href="#">Pago en Linea</b-dropdown-item>
          <b-dropdown-item href="#">Pago Referenciado</b-dropdown-item>
          

        </b-nav-item-dropdown>
      </b-navbar-nav>
    </nav>
  </div>
</template>

<script>
    export default {

    }         

</script>

<style scoped>
 .navbar.navbar-dark.bg-dark{
    background-color:#013b6d!important;
    width: 100%;
    position: fixed;
    z-index: 100;
  }

</style>