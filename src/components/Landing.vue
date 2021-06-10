<template>
  <body>
  <section class="hero is-info is-medium is-bold">
    <div class="hero-head">
      <nav class="navbar">
        <div class="container">
          <div class="navbar-brand">
            <a class="navbar-item">
              <!--              <img class="logo-wids-cdmx" alt="Logo" src="@/assets/logos/wids_cdmx_logo.png">-->
            </a>
            <span class="navbar-burger burger" data-target="navbarMenu">
              <span></span>
              <span></span>
              <span></span>
            </span>
          </div>
          <div id="navbarMenu" class="navbar-menu">
            <div class="navbar-end">
              <div class="tabs is-right">
                <ul>
                  <li><a href="#about-wids">Acerca de WiDS</a></li>
                  <li><a href="#agenda">Agenda</a></li>
                  <li><a href="#ponentes">Ponentes</a></li>
                  <li><a href="#registro">Registro</a></li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </nav>
    </div>
    <div class="hero-body">
      <div class="container has-text-centered">
        <img alt="Logo" class="logo-wids-cdmx" src="@/assets/logos/wids_cdmx_logo.png">
        <h1 class="title">
          Women in Data Science
        </h1>
        <h1 class="title">
          Ciudad de México
        </h1>
        <h2 class="subtitle">
          27 de junio, 2021 - Evento virtual
        </h2>
      </div>
    </div>
  </section>

  <!-- Acerca de Wids -->
  <div id="about-wids" class="section-light about-me">
    <div class="container">
      <div class="column is-12 about-me">
        <h1 class="title has-text-centered section-title">Acerca de WiDS</h1>
      </div>
      <div class="columns is-multiline">
        <div class="column is-6 has-vertically-aligned-content" data-aos="fade-right">
          <br/>
          <p>
            La conferencia mundial WiDS (Women in Data Science) tiene como objetivo inspirar y educar a lxs científicxs
            de datos de todo el mundo sin importar su género, así como dar apoyo a las mujeres presentes en la
            industria.
            Esta conferencia brinda una oportunidad para escuchar acerca de las últimas investigaciones y aplicaciones
            relacionadas con la ciencia de datos en distintos dominios y así conectar con otrxs en el campo.
          </p>
          <br/>
          <div class="is-divider"></div>
        </div>
        <div class="column is-6 right-image " data-aos="fade-left">
          <iframe allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen frameborder="0" height="315"
                  src="https://www.youtube.com/embed/yObQ-odcIKc"
                  title="YouTube video player"
                  width="560"></iframe>
        </div>
      </div>
    </div>
  </div>

  <!-- Agenda -->
  <div id="agenda" class="section-light about-me">
    <div class="container">
      <div class="column is-12 about-me">
        <h1 class="title has-text-centered section-title">Agenda</h1>
      </div>

      <table class="table is-striped">
        <tbody>
        <tr>
          <td>9:45 a 10:00</td>
          <td>Bienvenida</td>
          <td>Comité organizador</td>
        </tr>

        <tr>
          <td>10:00 a 10:30</td>
          <td>Los datos antes de la ciencia</td>
          <td id="teresita-guerrero">Teresita Guerrero</td>
        </tr>

        <tr>
          <td>10:30 a 11:00</td>
          <td>Pronósticos con inteligencia artificial</td>
          <td id="cristina-ortunio">Cristina Ortuño</td>
        </tr>

        <tr>
          <td>11:00 a 11:30</td>
          <td>
            <a href="https://www.youtube.com/watch?v=hdHdVW8eCJ8&list=PLHAk3jHXWpxL5M8AqtSGhfIPH5QeVcvhT&index=7" target="_blank">
              ¿Qué significa tener un algoritmo robusto? Mirar a través de lentes a conjunto de puntos
            </a>
          </td>
          <td id="cindy-orozo">Cindy Orozco</td>
        </tr>

        <tr>
          <td>11:30 a 12:00</td>
          <td>Coffe break</td>
          <td></td>
        </tr>

        <tr>
          <td>12:00 a 12:30</td>
          <td>Datos en Publicidad</td>
          <td id="silvia-ariza">Silvia Ariza Sentis</td>
        </tr>

        <tr>
          <td>12:30 a 13:00</td>
          <td>TBA</td>
          <td id="malitzin-cortes">Malitzin Cortés</td>
        </tr>

        <tr>
          <td>13:00 a 13:30</td>
          <td>
            <a href="https://www.youtube.com/watch?v=QdVMZXWWQh0&list=PLHAk3jHXWpxL5M8AqtSGhfIPH5QeVcvhT&index=29" target="_blank">
              Visualización de Datos como Medio Exploratorio: de la Percepción Científica a la Expresión Artística
            </a>
          </td>
          <td id="Fernanda Viegas">Fernanda Viegas</td>
        </tr>

        <tr>
          <td>13:30 a 15:00</td>
          <td>Comida</td>
          <td></td>
        </tr>

        <tr>
          <td>15:00 a 15:30</td>
          <td>Accesibilidad para la visualización de datos, A11 y DataViz</td>
          <td id="magaly-ruiz">Magaly Ruiz</td>
        </tr>

        <tr>
          <td>15:30 a 16:00</td>
          <td>La inmunología y R, grandes aliados</td>
          <td id="ana-villasenior">Ana Beatriz Villaseñor</td>
        </tr>

        <tr>
          <td>16:00 a 16:30</td>
          <td>Creando un app de descarga de series de tiempo financieras</td>
          <td id="tzolquin-gardunio">Tzolquin Garduño</td>
        </tr>

        <tr>
          <td>16:30 a 17:00</td>
          <td>Coffe break</td>
          <td></td>
        </tr>

        <tr>
          <td>17:00 a 18:00</td>
          <td>Panel: Ciencia de datos más allá del código</td>
          <td id="panel">
            <p>Ivete Sánchez</p>
            <p>Angelina Alarcon</p>
            <p>María de la Paz Rico</p>
            <p>Libertad Pantoja</p>
            <p>Ana Beatriz Villaseñor</p>
            <p>Karen Nuñez</p>
          </td>
        </tr>

        <tr>
          <td>18:00 a 18:15</td>
          <td>Clausura</td>
          <td>Comité organizador</td>
        </tr>
        </tbody>
      </table>

    </div>
  </div>


  </body>
</template>

<script>
export default {
  name: 'Landing',
  // props: {
  //   msg: String
  // }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
html, body {
  background: #EFF3F4;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen-Sans, Ubuntu, Cantarell, "Helvetica Neue", sans-serif;
}

.hero-body {
  background-image: url("/src/assets/cdmx-150027_1280.png");
  background-color: #00b140;
}

.hero .navbar {
  background-color: #00b140;
}


.hero-body .container {
  max-width: 700px;
}

.hero-body .title {
  color: hsl(192, 17%, 99%) !important;
}

.hero-body .subtitle {
  color: hsl(192, 17%, 99%) !important;
  padding-top: 2rem;
  line-height: 1.5;
}

.logo-wids-cdmx {
  width: 200px;
  height: 100%;
}

.table {
  margin-left: auto;
  margin-right: auto;
}

.features {
  padding: 5rem 0;
}

.box.cta {
  border-radius: 0;
  border-left: none;
  border-right: none;
}

.card-image > .fa {
  font-size: 8rem;
  padding-top: 2rem;
  padding-bottom: 2rem;
  color: #209cee;
}

.card-content .content {
  font-size: 14px;
  margin: 1rem 1rem;
}

.card-content .content h4 {
  font-size: 16px;
  font-weight: 700;
}

.card {
  box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.18);
  margin-bottom: 2rem;
}

.intro {
  padding: 5rem 0;
  text-align: center;
}

.sandbox {
  padding: 5rem 0;
}

.tile.notification {
  display: flex;
  justify-content: center;
  flex-direction: column;
}

.is-shady {
  animation: flyintoright .4s backwards;
  background: #fff;
  box-shadow: rgba(0, 0, 0, .1) 0 1px 0;
  border-radius: 4px;
  display: inline-block;
  margin: 10px;
  position: relative;
  transition: all .2s ease-in-out;
}

.is-shady:hover {
  box-shadow: 0 10px 16px rgba(0, 0, 0, .13), 0 6px 6px rgba(0, 0, 0, .19);
}

/*adds font awesome stars*/
footer li:before {
  content: '\f1b2';
  font-family: 'FontAwesome';
  float: left;
  margin-left: -1.5em;
  color: #147efb;
}
</style>
