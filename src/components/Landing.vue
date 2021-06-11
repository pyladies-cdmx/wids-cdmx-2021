<template>
  <body>
  <section class="hero is-info is-medium is-bold">
    <div class="hero-head">
      <nav class="navbar is-fixed-top">
        <div class="container">
          <div class="navbar-brand">
            <a class="navbar-item"></a>
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
                  <li><a href="#inicio">Inicio</a></li>
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
    <div id="inicio" class="hero-body">
      <div class="container has-text-centered">
        <img alt="Logo" class="logo-wids-cdmx" src="@/assets/logos/wids_cdmx_logo.png">
        <h1 class="title">
          Women in Data Science
        </h1>
        <h1 class="title">
          Ciudad de México
        </h1>
        <h2 class="subtitle">
          26 de junio, 2021 - Evento virtual
        </h2>
      </div>
    </div>
  </section>

  <!-- Acerca de Wids -->
  <div id="about-wids" class="section about-me">
    <div class="container">
      <div class="column is-12 about-me">
        <h1 class="title has-text-centered section-title">Acerca de WiDS</h1>
      </div>
      <br/>
      <div class="columns is-multiline">
        <div class="column is-6 has-vertically-aligned-content" data-aos="fade-right">
          <br/>
          <br/>
          <p>
            La conferencia mundial WiDS (Women in Data Science) tiene como objetivo inspirar y educar a lxs científicxs
            de datos de todo el mundo sin importar su género, así como dar apoyo a las mujeres presentes en la
            industria.</p>
          <br/>
          <p>Esta conferencia brinda la oportunidad de escuchar acerca de las últimas investigaciones y aplicaciones
            relacionadas con la ciencia de datos en distintos dominios y así conectar con otrxs en el campo.
          </p>
          <br/>
          <div class="is-divider"></div>
        </div>
        <div class="column is-6 right-image " data-aos="fade-left">
          <div class="contenido-responsivo">
            <iframe allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                    allowfullscreen frameborder="0" height="315"
                    src="https://www.youtube.com/embed/yObQ-odcIKc"
                    title="YouTube video player"
                    width="560"></iframe>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Agenda -->
  <div id="agenda" class="section">
    <div class="container">
      <div class="column is-12 about-me">
        <h1 class="title has-text-centered section-title">Agenda</h1>
      </div>
      <br/>
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
          <td><a href="#teresita-guerrero">Teresita Guerrero</a></td>
        </tr>

        <tr>
          <td>10:30 a 11:00</td>
          <td>Pronósticos con inteligencia artificial</td>
          <td><a href="#cristina-ortunio">Cristina Ortuño</a></td>
        </tr>

        <tr>
          <td>11:00 a 11:30</td>
          <td>
            <a href="https://www.youtube.com/watch?v=hdHdVW8eCJ8&list=PLHAk3jHXWpxL5M8AqtSGhfIPH5QeVcvhT&index=7"
               target="_blank">
              <p>¿Qué significa tener un algoritmo robusto?</p>
              <p>Mirar a través de lentes a conjunto de puntos</p>
            </a>
          </td>
          <td>Cindy Orozco</td>
        </tr>

        <tr>
          <td>11:30 a 12:00</td>
          <td>Coffee break</td>
          <td></td>
        </tr>

        <tr>
          <td>12:00 a 12:30</td>
          <td>Datos en Publicidad</td>
          <td><a href="#silvia-ariza">Silvia Ariza</a></td>
        </tr>

        <tr>
          <td>12:30 a 13:00</td>
          <td><i>Por confirmar</i></td>
          <td><a href="#malitzin-cortes">Malitzin Cortés</a></td>
        </tr>

        <tr>
          <td>13:00 a 13:30</td>
          <td>
            <a href="https://www.youtube.com/watch?v=QdVMZXWWQh0&list=PLHAk3jHXWpxL5M8AqtSGhfIPH5QeVcvhT&index=29"
               target="_blank">
              <p>Visualización de Datos como Medio Exploratorio:</p>
              <p>de la Percepción Científica a la Expresión Artística</p>
            </a>
          </td>
          <td>Fernanda Viegas</td>
        </tr>

        <tr>
          <td>13:30 a 15:00</td>
          <td>Comida</td>
          <td></td>
        </tr>

        <tr>
          <td>15:00 a 15:30</td>
          <td>Accesibilidad para la visualización de datos, A11 y DataViz</td>
          <td><a href="#magaly-ruiz">Magaly Ruiz</a></td>
        </tr>

        <tr>
          <td>15:30 a 16:00</td>
          <td>La inmunología y R, grandes aliados</td>
          <td><a href="#ana-villasenior">Ana Beatriz Villaseñor</a></td>
        </tr>

        <tr>
          <td>16:00 a 16:30</td>
          <td>Creando un app de descarga de series de tiempo financieras</td>
          <td><a href="#tzolquin-gardunio">Tzolquin Garduño</a></td>
        </tr>

        <tr>
          <td>16:30 a 17:00</td>
          <td>Coffee break</td>
          <td></td>
        </tr>

        <tr>
          <td>17:00 a 18:00</td>
          <td>Panel: Ciencia de datos más allá del código</td>
          <td>
            <p><a href="#ivete-sanchez">Ivete Sánchez, </a></p>
            <p><a href="#angelina-alarcon">Angelina Alarcon, </a></p>
            <p><a href="#maria-paz">María de la Paz Rico, </a></p>
            <p><a href="#libertad-pantoja">Libertad Pantoja, </a></p>
            <p><a href="#ana-villasenior">Ana Beatriz Villaseñor, </a></p>
            <p><a href="#karen-nunez">Karen Nuñez, </a></p>
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


  <!-- Ponentes -->
  <div id="ponentes" class="section">
    <div class="container">
      <div class="column is-12 about-me">
        <h1 class="title has-text-centered section-title">Ponentes</h1>
      </div>
      <br/>

      <!--      Primer set-->
      <div class="columns">
        <div class="column is-3">
          <div id="tzolquin-gardunio" class="card">
            <div class="card-image is-4by4">
              <figure class="image is-4by4">
                <a onclick="document.getElementById('modal-tzolkin').style.display='block'">
                  <img class="imagen-ponente" src="@/assets/img/tzolkin_gardunio.jpeg">
                </a>
              </figure>
            </div>
            <div class="card-content">
              <p class="title is-4 has-text-centered">
                <a onclick="document.getElementById('modal-tzolkin').style.display='block'">
                  Tzolquin Garduño
                </a>
              </p>
            </div>
          </div>
        </div>

        <div id="modal-tzolkin" class="modal">
          <div class="modal-background"></div>
          <div class="modal-content is-tiny">
            <div class="card interno">
              <div class="card-image interno">
                <figure class="image">
                  <img class="imagen-ponente-interna" src="@/assets/img/tzolkin_gardunio.jpeg">
                </figure>
              </div>
              <div class="card-content">
                <div class="media">
                  <div class="content">
                    <p class="title is-4">Tzolkin Garduño</p>
                  </div>
                </div>
                <div class="content">
                  Tzolkin Garduño ha incursionado en las mátemáticas aplicadas al cómputo, en el cómputo aplicado a la
                  medicina, en desarrollo de tecnologías blockchain, aprendizaje de máquina e inteligencia artificial.
                  Todo lo anterior con una perspectiva de aportación y crecimiento social.
                  <br>
                </div>
              </div>
            </div>
          </div>
          <button aria-label="close" class="modal-close is-large"
                  onclick="document.getElementById('modal-tzolkin').style.display='none'"></button>
        </div>


        <div class="column is-3">
          <div id="malitzin-cortes" class="card">
            <div class="card-image is4by4">
              <figure class="image is-4by4">
                <a onclick="document.getElementById('modal-malitzin').style.display='block'">
                  <img class="imagen-ponente" src="@/assets/img/malitzin_cortes.jpg">
                </a>
              </figure>
            </div>
            <div class="card-content">
              <p class="title is-4 has-text-centered">
                <a onclick="document.getElementById('modal-malitzin').style.display='block'">
                  Malitzin Cortés
                </a>
              </p>
            </div>
          </div>
        </div>

        <div id="modal-malitzin" class="modal">
          <div class="modal-background"></div>
          <div class="modal-content is-tiny">
            <div class="card interno">
              <div class="card-image interno">
                <figure class="image">
                  <img class="imagen-ponente-interna" src="@/assets/img/malitzin_cortes.jpg">
                </figure>
              </div>
              <div class="card-content">
                <div class="media">
                  <div class="content">
                    <p class="title is-4">Malitzin Cortés</p>
                  </div>
                </div>
                <div class="content">
                  <p>Su trabajo se desarrolla entre live coding, live cinema, instalación, realidad virtual, creative
                    coding, diseño sonoro , música experimental y arte sonoro.</p>
                  <p>Es profesora e investigadora de la Universidad <i>CENTRO - Diseño, Cine y Televisión</i> en el
                    campo
                    del código creativo, STEAM y nuevas tecnologías de sonido e inmersivas. En 2020 recibió el premio
                    Latinoamericano de Realidad Virtual “Realmix” con la pieza inmersiva “Hyper_D”.</p>
                  <p>Actualmente imparte el taller de live coding con programación funcional, Tidal cycles, en la
                    plataforma de educación en línea del CMMAS.</p>
                  <p>Ha realizado eventos en vivo y exposiciones en el Centro Multimedia, Laboratorio de Arte Alameda,
                    Arte Actual Ex-Teresa, Centro Cultural Digital, Medialab Prado, Centro Cultural de España, CMMAS,
                    Vorspiel, Spektrum Berlin, Transpiksel, Aural, Transmediale Berlin, ISEA, CYLAND MediaArtLab San
                    Petesburgo, ADAF, Ars Electronica, Currents, MUTEK México, Montreal y Japón.</p>
                  <p>La propuesta sonora del CNDSD se concibe en un ambiente experimental y ejercicios musicales
                    transfronterizos: paisajes granulares, experimentos vocales algorítmicos, improvisaciones de ruido
                    hipnótico, codificación en vivo y patrones asimétricos.</p>
                  <p>Como artista, investiga las formas en que el arte, la arquitectura, la tecnología y la ciencia
                    tienen
                    la capacidad de ser grandes divulgadores de hallazgos y dispositivos de autorreflexión y generación
                    de
                    modelos inéditos de interacciones sociales capaces de brindar nuevas formas de relacionarse desde el
                    utopía, especulación, espacio físico, realidad, el constante estado de crisis y también de
                    esperanza.</p>
                  <br>
                </div>
              </div>
            </div>
          </div>
          <button aria-label="close" class="modal-close is-large"
                  onclick="document.getElementById('modal-malitzin').style.display='none'"></button>
        </div>

        <div class="column is-3">
          <div id="magaly-ruiz" class="card">
            <div class="card-image">
              <figure class="image is-4by4">
                <a onclick="document.getElementById('modal-magaly').style.display='block'">
                  <img class="imagen-ponente" src="@/assets/img/magaly_ruiz.jpg">
                </a>
              </figure>
            </div>
            <div class="card-content">
              <p class="title is-4 has-text-centered">
                <a onclick="document.getElementById('modal-magaly').style.display='block'">
                  Magaly Ruiz
                </a>
              </p>
            </div>
          </div>
        </div>

        <div id="modal-magaly" class="modal">
          <div class="modal-background"></div>
          <div class="modal-content is-tiny">
            <div class="card interno">
              <div class="card-image interno">
                <figure class="image">
                  <img class="imagen-ponente-interna" src="@/assets/img/magaly_ruiz.jpg">
                </figure>
              </div>
              <div class="card-content">
                <div class="media">
                  <div class="content">
                    <p class="title is-4">Magaly Ruiz</p>
                  </div>
                </div>
                <div class="content">
                  <p>Ingeniera electrónica en computación con más de diez años de experiencia creando aplicaciones web.
                    Ha
                    trabajado en equipos pequeños de desarrollo nacionales e internacionales.</p>
                  <p>Actualmente forma parte del equipo de trabajo de la Subdirección de Visualización de Datos del
                    CONACYT y es Líder Técnica del equipo de desarrollo de la Dirección de Análisis de la Información.
                    Ahí
                    colabora en la creación de micrositios, visualizaciones y reportes de datos, para la difusión de
                    investigaciones en torno a problemáticas nacionales</p>
                  <br>
                </div>
              </div>
            </div>
          </div>
          <button aria-label="close" class="modal-close is-large"
                  onclick="document.getElementById('modal-magaly').style.display='none'"></button>
        </div>


        <div class="column is-3">
          <div id="libertad-pantoja" class="card">
            <div class="card-image">
              <figure class="image is-4by4">
                <a onclick="document.getElementById('modal-libertad').style.display='block'">
                  <img class="imagen-ponente" src="@/assets/img/libertad_pantoja.jpg">
                </a>
              </figure>
            </div>
            <div class="card-content">
              <p class="title is-4 has-text-centered">
                <a onclick="document.getElementById('modal-libertad').style.display='block'">
                  Libertad Pantoja
                </a>
              </p>
            </div>
          </div>
        </div>

        <div id="modal-libertad" class="modal">
          <div class="modal-background"></div>
          <div class="modal-content is-tiny">
            <div class="card interno">
              <div class="card-image interno">
                <figure class="image">
                  <img class="imagen-ponente-interna" src="@/assets/img/libertad_pantoja.jpg">
                </figure>
              </div>
              <div class="card-content">
                <div class="media">
                  <div class="content">
                    <p class="title is-4">Libertad Pantoja</p>
                  </div>
                </div>
                <div class="content">
                  <p>Estudió la licenciatura en Ciencias Genómicas y el
                    Doctorado en Ciencias Biomédicas en la UNAM. Es egresada del Diplomado en Escritura Literaria del
                    Centro Mexicano de Escritores. Ha sido analista bioinformática y científica de datos. Actualmente se
                    desempeña como escritora técnica y escritora de ficción.</p>
                  <br>
                </div>
              </div>
            </div>
          </div>
          <button aria-label="close" class="modal-close is-large"
                  onclick="document.getElementById('modal-libertad').style.display='none'"></button>
        </div>
      </div>


      <!--      Segundo Set-->
      <div class="columns">

        <div class="column is-3">
          <div id="karen-nunez" class="card">
            <div class="card-image">
              <figure class="image is-4by4">
                <img class="imagen-ponente" src="@/assets/img/karen_nunez.jpg">
              </figure>
            </div>
            <div class="card-content">
              <p class="title is-4 has-text-centered">
                <!--                <a onclick="document.getElementById('modal-Karen').style.display='block'">-->
                Karen Nuñez
                <!--                </a>-->
              </p>
              <div class="content">
                <br>
              </div>
            </div>
          </div>
        </div>

        <div class="column is-3 is-collapsible">
          <div id="ivete-sanchez" class="card">
            <div class="card-image">
              <figure class="image is-4by4">
                <a onclick="document.getElementById('modal-ivete').style.display='block'">
                  <img class="imagen-ponente" src="@/assets/img/ivete_sanchez.jpeg">
                </a>
              </figure>
            </div>
            <div class="card-content">
              <p class="title is-4 has-text-centered">
                <a onclick="document.getElementById('modal-ivete').style.display='block'">
                  Ivette Sánchez
                </a>
              </p>
            </div>
          </div>
        </div>
        <div id="modal-ivete" class="modal">
          <div class="modal-background"></div>
          <div class="modal-content is-tiny">
            <div class="card interno">
              <div class="card-image interno">
                <figure class="image">
                  <img class="imagen-ponente-interna" src="@/assets/img/ivete_sanchez.jpeg">
                </figure>
              </div>
              <div class="card-content">
                <div class="media">
                  <div class="content">
                    <p class="title is-4">Ivette Sánchez</p>
                  </div>
                </div>
                <div class="content">
                  <p>Ingeniera en Sistemas Computacionales de la Escuela Superior de Cómputo del Instituto Politécnico
                    Nacional. Maestra en Ciencias de la Computación y Matemáticas Industriales por el Centro de
                    Investigación en Matemáticas</p>
                  <p>Trabajó en la industria privada como líder de plataformas de optimización en Prolec-GE. Cuenta con
                    más de 15 años de experiencia en desarrollo de proyectos de software y de cómputo matemático y
                    transferencia de tecnología. Sus principales intereses y desarrollos son en las áreas de
                    procesamiento
                    de imágenes, machine learning, optimización, cómputo paralelo, reconocimiento de patrones y
                    modelación
                    numérica. Tiene certificaciones en ITIL, COBIT y como parte de un equipo Scrum Development(CSD),
                    además de formación en Administración de proyectos. Fue líder institucional por parte del CIMAT en
                    los
                    Nodos Binacionales de Innovación, tanto del Bajío como del Sureste.</p>
                  <p>Actualmente es Coordinadora de Servicios Tecnológicos del Centro de Investigación en Matemáticas y
                    Gerente del Consorcio de Inteligencia Artificial de Centros CONACyT, alianza conformada por ocho
                    centros públicos de investigación.</p>
                  <br>
                </div>
              </div>
            </div>
          </div>
          <button aria-label="close" class="modal-close is-large"
                  onclick="document.getElementById('modal-ivete').style.display='none'"></button>
        </div>

        <div class="column is-3">
          <div id="teresita-guerrero" class="card">
            <div class="card-image">
              <figure class="image is-4by4">
                <img class="imagen-ponente" src="@/assets/img/user.jpg">
              </figure>
            </div>
            <div class="card-content">
              <p class="title is-4 has-text-centered">
                <!--                <a onclick="document.getElementById('modal-teresita').style.display='block'">-->
                Teresita Guerrero
                <!--              </a>-->
              </p>
              <div class="content">
                <br>
              </div>
            </div>
          </div>
        </div>


        <div class="column is-3">
          <div id="cristina-ortunio" class="card">
            <div class="card-image">
              <figure class="image is-4by4">
                <a onclick="document.getElementById('modal-cristina').style.display='block'">
                  <img class="imagen-ponente" src="@/assets/img/cristina_ortunio.jpeg">
                </a>
              </figure>
            </div>
            <div class="card-content">
              <p class="title is-4 has-text-centered">
                <a onclick="document.getElementById('modal-cristina').style.display='block'">
                  Cristina Ortuño
                </a>
              </p>
            </div>
          </div>
        </div>

        <div id="modal-cristina" class="modal">
          <div class="modal-background"></div>
          <div class="modal-content is-tiny">
            <div class="card interno">
              <div class="card-image interno">
                <figure class="image">
                  <img class="imagen-ponente-interna" src="@/assets/img/cristina_ortunio.jpeg">
                </figure>
              </div>
              <div class="card-content">
                <div class="media">
                  <div class="content">
                    <p class="title is-4">Cristina Ortuño</p>
                  </div>
                </div>
                <div class="content">
                  <p>Estudió en la Universidad Nacional Autónoma de México la carrera de actuaría y la maestría en
                    estadística. Fue docente por 5 años en temas de simulación y estadística, trabajó en instituciones
                    gubernamentales, en temas de calidad del aire por 16 años, en temas de derechos humanos por 2 años y
                    en la función pública por 2 años; durante este tiempo sus principales actividades fueron la
                    verificación y validación de datos, la generación de indicadores, modelación y análisis de
                    encuestas.
                    Posteriormente, por 7 años se desempeñó como consultora independiente desarrollando proyectos a
                    nivel
                    nacional y colaboró con varias consultorías para desarrollar proyectos nacionales e internacionales
                    en
                    temas de gestión ambiental (calidad del aire, inventarios de emisiones) y otorgó cursos de
                    capacitación de manejo de datos y generación de indicadores. En el último año estudió temas de
                    inteligencia artificial y programación de lenguaje natural; obtuvo con su equipo el tercer lugar por
                    desarrollar un modelo de pronóstico de concentración de partículas finas en la primera edición de AI
                    Saturdays Latam; participó en un hackathon de cambio climático organizado por el gobierno de Canadá
                    y
                    AI Launch Lab, donde ella y su equipo fueron ganadores en la categoría de pronóstico de demanda de
                    energía eólica. Actualmente trabaja como científica de datos en el Instituto Mexicano para la
                    Competitividad, una asociación civil que desarrolla proyectos de investigación encaminados a evaluar
                    la competitividad del país.</p>
                  <br>
                </div>
              </div>
            </div>
          </div>
          <button aria-label="close" class="modal-close is-large"
                  onclick="document.getElementById('modal-cristina').style.display='none'"></button>
        </div>
      </div>

      <!--      Tercer Set-->
      <div class="columns">

        <div class="column is-3 is-collapsible">
          <div id="silvia-ariza" class="card">
            <div class="card-image">
              <figure class="image is-4by4">
                <img class="imagen-ponente" src="@/assets/img/user.jpg">
              </figure>
            </div>
            <div class="card-content">
              <p class="title is-4 has-text-centered">
                <!--                <a onclick="document.getElementById('modal-silvia').style.display='block'">-->
                Silvia Ariza
                <!--                </a>-->
              </p>
              <div class="content">
                <br>
              </div>
            </div>
          </div>
        </div>

        <div class="column is-3">
          <div id="ana-villasenior" class="card">
            <div class="card-image">
              <figure class="image is-4by4">
                <img class="imagen-ponente" src="@/assets/img/user.jpg">
              </figure>
            </div>
            <div class="card-content">
              <p class="title is-4 has-text-centered">
                <!--                <a onclick="document.getElementById('modal-ana').style.display='block'">-->
                Ana Beatriz Villaseñor
                <!--              </a>-->
              </p>
              <div class="content">
                <br>
              </div>
            </div>
          </div>
        </div>

        <div class="column is-3">
          <div id="angelina-alarcon" class="card">
            <div class="card-image">
              <figure class="image is-4by4">
                <img class="imagen-ponente" src="@/assets/img/user.jpg">
              </figure>
            </div>
            <div class="card-content">
              <p class="title is-4 has-text-centered">
                <!--                <a onclick="document.getElementById('modal-angelina').style.display='block'">-->
                Angelina Alarcón
                <!--              </a>-->
              </p>
              <div class="content">
                <br>
              </div>
            </div>
          </div>
        </div>

        <div class="column is-3">
          <div id="maria-paz" class="card">
            <div class="card-image">
              <figure class="image is-4by4">
                <img class="imagen-ponente" src="@/assets/img/user.jpg">
              </figure>
            </div>
            <div class="card-content">
              <p class="title is-4 has-text-centered">
                <!--                <a onclick="document.getElementById('modal-maria').style.display='block'">-->
                Maria de la Paz Rico
                <!--              </a>-->
              </p>
              <div class="content">
                <br>
              </div>
            </div>
          </div>
        </div>

      </div>

    </div>
  </div>

  <!-- Registro -->
  <div id="registro" class="section">
    <div class="container">
      <div class="column is-12 about-me">
        <h1 class="title has-text-centered section-title">Registro</h1>
      </div>
      <div class="columns is-multiline">
        <div id="registro-container" class="column is-12 has-vertically-aligned-content" data-aos="fade-right">
          <br/>
          <p>Por favor regístrate a través del siguiente enlace. Antes del evento se enviarán las instrucciones para que
            puedas acceder al mismo.</p>
          <p>El evento se llevará acabo en la plataforma Eulerr el día 26 de Junio y con cupo limitado.</p>
          <br/>
          <button class="button is-dark is-large">
            <a class="boton-registro"
               href="https://docs.google.com/forms/d/e/1FAIpQLScceJ72WnpsP1YTKbNW69JYMdAlGEjy8IxQsj6cTsSgeuIzcg/viewform?usp=sf_link"
               target="_blank">
              Regístrate
            </a>
          </button>
          <br/>
        </div>
      </div>
    </div>
  </div>

  <!--  Footer-->
  <footer class="footer">
    <div class="container">
      <div id="columns-footer" class="columns has-text-centered">
        <div class="column is-2">
          <img class="logo-pyladies-cdmx" src="@/assets/logos/pyladies_logo.png">
        </div>
        <div class="column is-1">
          <p>
            <a class="link-footer" href="https://www.facebook.com/pyladiescdmx" target="_blank">Facebook</a>
          </p>
        </div>
        <div class="column is-1">
          <p>
            <a class="link-footer" href="https://www.instagram.com/pyladiescdmx/" target="_blank">Instagram</a>
          </p>
        </div>
        <div class="column is-1">
          <p>
            <a class="link-footer" href="https://twitter.com/mxpyladies" target="_blank">Twitter</a>
          </p>
        </div>
        <div class="column is-1">
          <p>
            <a class="link-footer" href="https://www.meetup.com/Mexico-City-Pyladies-Meetup/" target="_blank">Meetup</a>
          </p>
        </div>
        <div class="column is-1">
          <p>
            <a class="link-footer" href="mailto: mx@pyladies.com" target="_blank">mx@pyladies.com</a>
          </p>
        </div>
      </div>
    </div>
  </footer>


  </body>
</template>

<script>
export default {
  name: 'Landing',
  mounted() {
    (function () {
      var burger = document.querySelector('.burger');
      var menu = document.querySelector('#' + burger.dataset.target);
      burger.addEventListener('click', function () {
        burger.classList.toggle('is-active');
        menu.classList.toggle('is-active');
      });
    })();
  }
}


</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
html, body {
  background: #EFF3F4;
  font-family: "Quatrocento Sans";
  font-size: 18px;
  /*font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen-Sans, Ubuntu, Cantarell, "Helvetica Neue", sans-serif;*/
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}

h1 {
  font-size: 40px;
}

.hero-body {
  /*background-image: url("/src/assets/cdmx-150027_1280.png");*/
  background-color: #00b140;
  height: 100vh;
}

.hero .navbar {
  background-color: #00b140;
}

.hero .navbar-menu {
  background-image: linear-gradient(141deg, #00b140 0, #00b140 50%, #00b140 100%) !important;
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
  width: 300px;
  height: 100%;
}

.logo-pyladies-cdmx {
  width: 80px;
  height: 100%;
}

.table {
  margin-left: auto;
  margin-right: auto;
}

#registro-container {
  text-align: center;
}

.card-image {
  background-color: #EFF3F4;
  font-size: 8rem;
  margin-left: auto;
  margin-right: auto;
  width: 100%;
}

.card-image.interno {
  background-color: #EFF3F4;
  font-size: 8rem;
  padding-top: 0.1rem;
  margin-top: 2rem;
  margin-left: auto;
  margin-right: auto;
  width: 100%;
}

.card-content .content {
  font-size: 18px;
  margin: 1rem 1rem;
}

.card-content .content h5 {
  font-size: 16px;
  font-weight: 700;
}

.card {
  background-color: #EFF3F4;
  box-shadow: none;
}

.card.interno {
  background-color: #EFF3F4;
  box-shadow: none;
  max-width: 80vw;
}

img.imagen-ponente {
  width: 259px;
  height: 259px;
  object-fit: cover;
  border-radius: 50%;
  overflow: hidden;
  margin-left: auto;
  margin-right: auto;
}

img.imagen-ponente-interna {
  width: 259px;
  height: 259px;
  object-fit: cover;
  border-radius: 50%;
  margin-top: 2rem;
  margin-bottom: 2rem;
  margin-left: auto;
  margin-right: auto;
}

footer {
  color: white;
  background-color: #00b140;
}

a:link {
  color: #00b140;
  background-color: transparent;
  text-decoration: none;
}

a:visited {
  color: #9494b8;
  background-color: transparent;
  text-decoration: none;
}

a:hover {
  color: #006600;
  background-color: transparent;
  text-decoration: underline;
}

a:active {
  color: white;
  background-color: transparent;
  text-decoration: underline;
}

a.link-footer:link {
  color: white;
  background-color: transparent;
  text-decoration: none;
}

a.link-footer:visited {
  color: white;
  background-color: transparent;
  text-decoration: none;
}

a.boton-registro:link {
  color: white;
  background-color: transparent;
  text-decoration: none;
}

a.boton-registro:visited {
  color: white;
  background-color: transparent;
  text-decoration: none;
}

a.boton-registro:hover {
  color: lightgrey;
  background-color: transparent;
  text-decoration: underline;
}

a {
  color: #363636;
  background-color: transparent;
  text-decoration: none;
}

.contenido-responsivo {
  position: relative;
  height: 0;
  overflow: hidden;
  padding-bottom: 56.2%;
  margin-bottom: 20px;
}

.contenido-responsivo iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

</style>
