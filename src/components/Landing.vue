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
                  <li><a href="">Acerca de WiDS</a></li>
                  <li><a href="">Agenda</a></li>
                  <li><a href="">Ponentes</a></li>
                  <li><a href="">Registro</a></li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </nav>
    </div>
    <div class="hero-body">
      <div class="container has-text-centered">
        <img class="logo-wids-cdmx" alt="Logo" src="@/assets/logos/wids_cdmx_logo.png">
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
