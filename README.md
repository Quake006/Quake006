## Hi there 👋

<!--
**Quake006/Quake006** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.



<!DOCTYPE html>
<html lang="es">

  <head>
    
    <meta charset="utf-8"/>
    <title>Mi portafolio</title>
    <meta name="viewport" content="width=device-width, initial-scale=1"/>

    <!-- CDN - Bootstrap -->
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-gH2yIJqKdNHPEq0n4Mqa/HGKIhSkIHeL5AyhkYV8i59U5AR6csBvApHHNl/vI1Bx"
      crossorigin="anonymous"
    />

    <!-- CDN - Bootstrap Iconos -->
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.9.1/font/bootstrap-icons.css"
    />

    <!-- CSS locales -->
    <link rel="stylesheet" href="css/style-body.css" />
    <link rel="stylesheet" href="css/style-header.css" />
    <link rel="stylesheet" href="css/style-articulos.css" />
    <link rel="stylesheet" href="css/style-skills.css" />

  </head>
 
  <body>

    <!-- ========= Developer profile -->
    <header class="container-fluid px-5 pt-3">
     
      <!-- Blank space -->
      <div class="row d-block d-md-none mb-5">
        <div class="d-flex justify-content-end">
        </div>
      </div>

      <!-- Foto de perfil -->
      <div class="row d-block d-md-none justify-content-center px-5 mb-3">
        <div class="col-12 d-flex justify-content-center">
          <div
            class="d-flex justify-content-center rounded-circle overflow-hidden circuloPerfil">
            <img src="img/perfil.jpg" alt="" style="width: 40px"/>
          </div>
        </div>
      </div>

      <!-- Nombre del desarrollador -->
      <div class="row d-block d-md-none justify-content-center">
        <div class="col-12 d-flex justify-content-center flex-column">
          <h1 class="Nombre mt-3 text-center">Raquel Casares</h1>
          <label class="Trabajo text-center">Junior Developer</label>
        </div>
      </div>
    </header>
    <!-- ========= -->

    <!-- Body main content -->
    <!-- ======== Diseño para dispositivos móviles ======== -->
    <section class="d-block d-md-none">
      <article class="px-5 pb-5">
        <!-- Información Principal -->
        <div
          class="d-block d-md-none justify-content-center d-flex flex-row mb-4 mt-4 rounded">
          <div class="d-flex flex-column">
            <label class="SubTitulos text-center w-100">
              Desarrolladora a tiempo completo, experta en el uso de diferentes
              tecnologías y gran apasionada de la programación.
            </label>
          </div>
        </div>

        <!-- Descargar curriculum y redes sociales -->
        <div
          class="d-block d-md-none d-flex flex-row justify-content-center py-2 px-2">
          <div class="d-flex justify-content-center">
            <a
              href="pdf/RAQUEL_CASARESDELAPOZA_CV.pdf"
              download
              rel="noopener noreferrer"
              target="_blank">
              <button
                type="button"
                name="button"
                class="btn btn-primary p-3 me-3 SubTitulos"
                style="font-size: 0.9rem">
                Descargar CV
                <i class="bi bi-download" style="font-size: 0.9rem"></i>
              </button>
            </a>
          </div>

          <div class="d-flex justify-content-center align-items-center">
            <a
              href="https://github.com/Quake006"
              target="_blank"
              type="button"
              class="btn btn-outline-primary">
              <i class="bi bi-github"></i>
            </a>
            <a
              href="mailto:raquelcasares82@gmail.com"
              type="button"
              class="btn btn-outline-primary ms-1">
              <i class="bi bi-envelope">
              </i>
            </a>
          </div>
        </div>

        <!-- Barra de tabs para moverse por el contenido de la página web -->
        <nav class="d-flex justify-content-center d-block d-md-none">
          <div
            class="nav nav-tabs my-4 px-4 d-flex justify-content-center border-0 py-3"
            id="nav-tab"
            role="tablist">
            <button
              class="nav-link active p-2 px-3 rounded border-0"
              id="nav-proyectos-tab"
              data-bs-toggle="tab"
              data-bs-target="#nav-proyectos"
              type="button"
              role="tab"
              aria-controls="nav-proyectos"
              aria-selected="true">
              Proyectos
            </button>

            <button
              class="nav-link p-3 px-3 rounded ms-2 border-0"
              id="nav-habilidades-tab"
              data-bs-toggle="tab"
              data-bs-target="#nav-habilidades"
              type="button"
              role="tab"
              aria-controls="nav-habilidades"
              aria-selected="false">
              Habilidades
            </button>
          </div>
        </nav>

        <!-- Paneles que contienen la información de los tabs -->
        <div class="tab-content d-block d-md-none" id="nav-tabContent">
          <div
            class="tab-pane fade show active"
            id="nav-proyectos"
            role="tabpanel"
            aria-labelledby="nav-proyectos-tab"
            tabindex="0">
            <!-- Muestra los proyectos en dispositivos pequeños -->
            <section class="d-block d-sm-none">
              <div class="d-flex justify-content-center" style=" margin-bottom: 35%;">
                <div
                  class="proyPeluditos d-flex flex-column overflow-hidden"
                  style="width: 280px; height: 200px">
                </div>
                <div class="text-light position-absolute" style="margin-top: 50%;">
                  <h4 class="SubTitulos" style="font-size: 1rem">Web Caninoterapia</h4>
                  <h3 class="Titulo">MiPeluditoSOS<a
                    href="pdf/Proyecto Integrado-DAW-Raquel Casares De la Poza.pdf"
                    download
                    rel="noopener noreferrer"
                    target="_blank">
                    <button
                      type="button"
                      name="button"
                      class="btn btn-primary rounded-pill">
                      <i class="bi bi-link"></i>
                    </button>
                    </a></h3>
                  
                </div>
              </div>

              <div class="d-flex justify-content-center mt-4" style=" margin-bottom: 35%;" >
                <div
                  class="proyComprasApp d-flex flex-column overflow-hidden"
                  style="width: 280px; height: 200px">
                </div>
                <div class="text-light position-absolute" style="margin-top: 50%;">
                  <h4 class="SubTitulos" style="font-size: 1rem">App Android</h4>
                  <h3 class="Titulo">MisComprasApp<a
                    href="pdf/Proyecto Integrado-Raquel Casares De la Poza.pdf"
                    download
                    rel="noopener noreferrer"
                    target="_blank">
                    <button
                      type="button"
                      name="button"
                      class="btn btn-primary rounded-pill">
                      <i class="bi bi-link"></i>
                    </button>
                    </a></h3>
                </div>
              </div>

              <div class="d-flex justify-content-center mt-4" style="margin-bottom: 35%;">
                <div
                  class="proyEgiptoWeb d-flex flex-column overflow-hidden"
                  style="width: 280px; height: 200px">
                </div>
                <div class="text-light position-absolute" style="margin-top: 50%;">
                  <h4 class="SubTitulos" style="font-size: 1rem">Web Egipto</h4>
                  <h3 class="Titulo">EgiptoWeb<a
                    href="pdf/Práctica 3-DIW-Raquel Casares De la Poza.pdf"
                    download
                    rel="noopener noreferrer"
                    target="_blank">
                    <button
                      type="button"
                      name="button"
                      class="btn btn-primary rounded-pill">
                      <i class="bi bi-link"></i>
                    </button>
                    </a></h3>
                </div>
              </div>

              <div class="d-flex justify-content-center mt-4" style="margin-bottom: 35%;">
                <div
                  class="proyMyAvatar d-flex flex-column overflow-hidden"
                  style="width: 280px; height: 200px">
                </div>
                <div class="text-light position-absolute" style="margin-top: 50%;">
                  <h4 class="SubTitulos" style="font-size: 1rem">App Android</h4>
                  <h3 class="Titulo">MyAvatar<a
                    href="pdf/Práctica 4-PMDM-Raquel Casares De la Poza.pdf"
                    download
                    rel="noopener noreferrer"
                    target="_blank">
                    <button
                      type="button"
                      name="button"
                      class="btn btn-primary rounded-pill">
                      <i class="bi bi-link"></i>
                    </button>
                    </a></h3>
                </div>
              </div>

              <div class="d-flex justify-content-center mt-4" style="margin-bottom: 35%;">
                <div
                  class="proyMiTiendecita d-flex flex-column overflow-hidden"
                  style="width: 280px; height: 200px">
                </div>
                <div class="text-light position-absolute" style="margin-top: 50%;">
                  <h4 class="SubTitulos" style="font-size: 1rem">App Web</h4>
                  <h3 class="Titulo">MiTiendecita<a
                    href="pdf/Práctica4-DAW-Raquel Casares De la Poza.pdf"
                    download
                    rel="noopener noreferrer"
                    target="_blank">
                    <button
                      type="button"
                      name="button"
                      class="btn btn-primary rounded-pill">
                      <i class="bi bi-link"></i>
                    </button>
                    </a></h3>
                </div>
              </div>

              <div class="d-flex justify-content-center mt-4" style="margin-bottom: -125%;">
                <div
                  class="proyProgramaGestion d-flex flex-column overflow-hidden"
                  style="width: 280px; height: 200px">
                </div>
                <div class="text-light position-absolute" style="margin-top: 50%; margin-bottom: -150%;">
                  <h4 class="SubTitulos" style="font-size: 1rem">App Escritorio</h4>
                  <h3 class="Titulo">Gestión Autoescuela<a
                    href="pdf/Programación 2-Manual Usuario-Raquel Casares De la Poza.pdf"
                    download
                    rel="noopener noreferrer"
                    target="_blank">
                    <button
                      type="button"
                      name="button"
                      class="btn btn-primary rounded-pill">
                      <i class="bi bi-link"></i>
                    </button>
                    </a></h3>
                </div>
              </div>

            </section>
          </div>
            <!-- Muestra los proyectos en dispositivos medianos -->
            <section class="d-none d-sm-block d-md-none">
              <div class="row" style="margin-bottom: 25%;">
                <div class="col-sm-6 d-flex justify-content-center">
                  <div
                    class="proyPeluditos d-flex flex-column overflow-hidden"
                    style="width: 400px; height: 200px">
                  </div>
                    <div class="text-light position-absolute" style="margin-top: 35%;">
                      <h4 class="SubTitulos" style="font-size: 1rem">Web Caninoterapia</h4>
                      <h3 class="Titulo">MiPeluditoSOS</h3>
                        <a
                        href="pdf/Proyecto Integrado-DAW-Raquel Casares De la Poza.pdf"
                        download
                        rel="noopener noreferrer"
                        target="_blank">
                        <button
                          type="button"
                          name="button"
                          class="btn btn-primary rounded-pill">
                          <i class="bi bi-link"></i>
                        </button>
                        </a>
                  </div>
                </div>

                <div class="col-sm-6 d-flex justify-content-center">
                  <div
                    class="proyComprasApp d-flex flex-column overflow-hidden"
                    style="width: 400px; height: 200px">
                  </div>
                  <div class="text-light position-absolute" style="margin-top: 35%;">
                    <h4 class="SubTitulos" style="font-size: 1rem">App Android</h4>
                    <h3 class="Titulo">MisComprasApp</h3>
                      <a
                      href="pdf/Proyecto Integrado-Raquel Casares De la Poza.pdf"
                      download
                      rel="noopener noreferrer"
                      target="_blank">
                      <button
                        type="button"
                        name="button"
                        class="btn btn-primary rounded-pill">
                        <i class="bi bi-link"></i>
                      </button>
                      </a>
                  </div>
                </div>
              </div>

              <div class="row" style="margin-bottom: 25%;">
                <div class="col-sm-6 d-flex justify-content-center">
                  <div
                    class="proyEgiptoWeb d-flex flex-column overflow-hidden"
                    style="width: 400px; height: 200px">
                  </div>
                  <div class="text-light position-absolute" style="margin-top: 35%;">
                    <h4 class="SubTitulos" style="font-size: 1rem">Web Egipto</h4>
                    <h3 class="Titulo">EgiptoWeb</h3>
                      <a
                      href="pdf/Práctica 3-DIW-Raquel Casares De la Poza.pdf"
                      download
                      rel="noopener noreferrer"
                      target="_blank">
                      <button
                        type="button"
                        name="button"
                        class="btn btn-primary rounded-pill">
                        <i class="bi bi-link"></i>
                      </button>
                      </a>
                  </div>
                </div>

                <div class="col-sm-6 d-flex justify-content-center">
                  <div
                    class="proyMyAvatar d-flex flex-column overflow-hidden"
                    style="width: 400px; height: 200px">
                  </div>
                  <div class="text-light position-absolute" style="margin-top: 35%;">
                    <h4 class="SubTitulos" style="font-size: 1rem">App Android</h4>
                    <h3 class="Titulo">MyAvatar</h3>
                      <a
                      href="pdf/Práctica 4-PMDM-Raquel Casares De la Poza.pdf"
                      download
                      rel="noopener noreferrer"
                      target="_blank">
                      <button
                        type="button"
                        name="button"
                        class="btn btn-primary rounded-pill">
                        <i class="bi bi-link"></i>
                      </button>
                      </a>
                  </div>
                </div>
              </div>

              <div class="row" style="margin-bottom: -5%;">
                <div class="col-sm-6 d-flex justify-content-center">
                  <div
                    class="proyMiTiendecita d-flex flex-column overflow-hidden"
                    style="width: 400px; height: 200px">
                  </div>
                  <div class="text-light position-absolute" style="margin-top: 35%;">
                    <h4 class="SubTitulos" style="font-size: 1rem">App Web</h4>
                    <h3 class="Titulo">MiTiendecita</h3>
                      <a
                      href="pdf/Práctica4-DAW-Raquel Casares De la Poza.pdf"
                      download
                      rel="noopener noreferrer"
                      target="_blank">
                      <button
                        type="button"
                        name="button"
                        class="btn btn-primary rounded-pill">
                        <i class="bi bi-link"></i>
                      </button>
                      </a>
                  </div>
                </div>

                <div class="col-sm-6 d-flex justify-content-center">
                  <div
                    class="proyProgramaGestion d-flex flex-column overflow-hidden"
                    style="width: 400px; height: 200px">
                  </div>
                  <div class="text-light position-absolute" style="margin-top: 35%;">
                    <h4 class="SubTitulos" style="font-size: 1rem">App Escritorio</h4>
                    <h3 class="Titulo">Gestión Autoescuela</h3>
                      <a
                      href="pdf/Programación 2-Manual Usuario-Raquel Casares De la Poza.pdf"
                      download
                      rel="noopener noreferrer"
                      target="_blank">
                      <button
                        type="button"
                        name="button"
                        class="btn btn-primary rounded-pill">
                        <i class="bi bi-link"></i>
                      </button>
                      </a>
                  </div>
                </div>
              </div>

            </section>
          </div>

          <!-- Muestra las habilidades del programador en dispositivos pequeños -->
          <div
            class="tab-pane fade"
            id="nav-habilidades"
            role="tabpanel"
            aria-labelledby="nav-habilidades-tab"
            tabindex="0">
            <section class="d-block d-sm-none">
              <div class="d-flex justify-content-center">
                <div class="skills__area">
                  <h3 class="skills__title">Desarrollo Frontend</h3>

                  <div class="skills__box">
                    <div class="skills__group">
                      <div class="skills__data">
                        <i
                          class="bi bi-patch-check"
                          style="color: var(--color-principal)">
                        </i>
                        <div>
                          <h3 class="skills__name">HTML</h3>
                         
                        </div>
                      </div>

                      <div class="skills__data">
                        <i
                          class="bi bi-patch-check"
                          style="color: var(--color-principal)">
                        </i>

                        <div>
                          <h3 class="skills__name">CSS</h3>
                          
                        </div>
                      </div>

                      <div class="skills__data">
                        <i
                          class="bi bi-patch-check"
                          style="color: var(--color-principal)">
                        </i>

                        <div>
                          <h3 class="skills__name">JavaScript</h3>
                          
                        </div>
                      </div>
                    </div>

                    <div class="skills__group">
                      <div class="skills__data">
                        <i
                          class="bi bi-patch-check"
                          style="color: var(--color-principal)">
                        </i>

                        <div>
                          <h3 class="skills__name">Android</h3>
                          
                        </div>
                      </div>

                      <div class="skills__data">
                        <i
                          class="bi bi-patch-check"
                          style="color: var(--color-principal)">
                        </i>

                        <div>
                          <h3 class="skills__name">Bootstrap</h3>
                         
                        </div>
                      </div>

                      <div class="skills__data">
                        <i
                          class="bi bi-patch-check"
                          style="color: var(--color-principal)">
                        </i>

                        <div>
                          <h3 class="skills__name">GitHub</h3>
                        
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>

              <div class="d-flex justify-content-center mt-4">
                <div class="skills__area">
                  <h3 class="skills__title">Desarrollo Backend</h3>

                  <div class="skills__box">
                    <div class="skills__group">
                      <div class="skills__data">
                        <i
                          class="bi bi-patch-check"
                          style="color: var(--color-principal)">
                        </i>

                        <div>
                          <h3 class="skills__name">PHP</h3>
                         
                        </div>
                      </div>

                      <div class="skills__data">
                        <i
                          class="bi bi-patch-check"
                          style="color: var(--color-principal)">
                        </i>

                        <div>
                          <h3 class="skills__name">MySQL</h3>
                         
                        </div>
                      </div>

                      <div class="skills__data">
                        <i
                          class="bi bi-patch-check"
                          style="color: var(--color-principal)">
                        </i>

                        <div>
                          <h3 class="skills__name">Java</h3>
                          
                        </div>
                      </div>
                    </div>

                    <div class="skills__group">
                      <div class="skills__data">
                        <i
                          class="bi bi-patch-check"
                          style="color: var(--color-principal)">
                        </i>

                        <div>
                          <h3 class="skills__name">JEE</h3>
                          
                        </div>
                      </div>

                      <div class="skills__data">
                        <i
                          class="bi bi-patch-check"
                          style="color: var(--color-principal)">
                        </i>

                        <div>
                          <h3 class="skills__name">Apache</h3>
                          
                        </div>
                      </div>

                      <div class="skills__data">
                        <i
                          class="bi bi-patch-check"
                          style="color: var(--color-principal)">
                        </i>

                        <div>
                          <h3 class="skills__name">MongoDB</h3>
                          
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </section>

            <!-- Muestra las habilidades en dispositivos medianos -->
            <section class="d-none d-sm-block d-md-none">
              <div class="row">
                <div class="col-sm-6 d-flex justify-content-center">
                  <div class="skills__area">
                    <h3 class="skills__title">Desarrollo Frontend</h3>

                    <div class="skills__box">
                      <div class="skills__group">
                        <div class="skills__data">
                          <i
                            class="bi bi-patch-check"
                            style="color: var(--color-principal)">
                          </i>

                          <div>
                            <h3 class="skills__name">HTML</h3>
                            
                          </div>
                        </div>

                        <div class="skills__data">
                          <i
                            class="bi bi-patch-check"
                            style="color: var(--color-principal)">
                          </i>

                          <div>
                            <h3 class="skills__name">CSS</h3>
                           
                          </div>
                        </div>

                        <div class="skills__data">
                          <i
                            class="bi bi-patch-check"
                            style="color: var(--color-principal)">
                          </i>

                          <div>
                            <h3 class="skills__name">JavaScript</h3>
                           
                          </div>
                        </div>
                      </div>

                      <div class="skills__group">
                        <div class="skills__data">
                          <i
                            class="bi bi-patch-check"
                            style="color: var(--color-principal)">
                          </i>

                          <div>
                            <h3 class="skills__name">Android</h3>
                            
                          </div>
                        </div>

                        <div class="skills__data">
                          <i
                            class="bi bi-patch-check"
                            style="color: var(--color-principal)">
                          </i>

                          <div>
                            <h3 class="skills__name">Bootstrap</h3>
                          
                          </div>
                        </div>

                        <div class="skills__data">
                          <i
                            class="bi bi-patch-check"
                            style="color: var(--color-principal)">
                          </i>

                          <div>
                            <h3 class="skills__name">GitHub</h3>
                            
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>

                <div class="col-sm-6 d-flex justify-content-center">
                  <div class="skills__area">
                    <h3 class="skills__title">Desarrollo Backend</h3>

                    <div class="skills__box">
                      <div class="skills__group">
                        <div class="skills__data">
                          <i
                            class="bi bi-patch-check"
                            style="color: var(--color-principal)">
                          </i>

                          <div>
                            <h3 class="skills__name">PHP</h3>
                            
                          </div>
                        </div>

                        <div class="skills__data">
                          <i
                            class="bi bi-patch-check"
                            style="color: var(--color-principal)">
                          </i>

                          <div>
                            <h3 class="skills__name">MySQL</h3>
                            
                          </div>
                        </div>

                        <div class="skills__data">
                          <i
                            class="bi bi-patch-check"
                            style="color: var(--color-principal)">
                          </i>

                          <div>
                            <h3 class="skills__name">Java</h3>
                           
                          </div>
                        </div>
                      </div>

                      <div class="skills__group">
                        <div class="skills__data">
                          <i
                            class="bi bi-patch-check"
                            style="color: var(--color-principal)">
                          </i>

                          <div>
                            <h3 class="skills__name">JEE</h3>
                            
                          </div>
                        </div>

                        <div class="skills__data">
                          <i
                            class="bi bi-patch-check"
                            style="color: var(--color-principal)">
                          </i>

                          <div>
                            <h3 class="skills__name">Apache</h3>
                            
                          </div>
                        </div>

                        <div class="skills__data">
                          <i
                            class="bi bi-patch-check"
                            style="color: var(--color-principal)">
                          </i>

                          <div>
                            <h3 class="skills__name">MongoDB</h3>
                            
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </section>
          </div>
        </div>

      </article>
    </section>
    
   
    <!-- ======== Cierre para dispositivos móviles ======== -->

    
    <!-- ======== Apertura para tablets y pantallas grandes lg ======== -->
    <div
    id="sobreMi"></div>
    <section class="d-none d-md-block pt-1">
      <nav class="navbar navbar-expand fixed-top px-5 barra-mobiles">
        <div class="container-fluid mt-3 mb-3 px-5">
          <a class="TituloBrand" href="#ini"> Raquel Casares </a>

          <div class="navbar-nav">

            <a class="TitulosNav" href="#sobreMi"> Sobre mí </a>

            <a class="TitulosNav" href="#habilidades"> Habilidades </a>

            <a class="TitulosNav" href="#proyectos"> Proyectos </a>

            <a class="TitulosNav" href="#experiencia"> Experiencia y Cursos </a>

            <a class="TitulosNav" href="#contacto"> Contacto </a>
          </div>
        </div>
      </nav>
  
      <!-- Información Principal -->
      
      <div
        id="inicio"
        class="mx-5 d-flex"
        style="margin-top: 80px; margin-bottom: 100px">
        <div
          class="w-25 d-flex py-5 mt-5 flex-column align-items-center">
          <a href="https://github.com/Quake006" target="_blank">
            <i
              class="bi bi-github icono_contacto"
              style="font-size: 30px;">
            </i>
          </a>
          <a
            href="mailto:raquelcasares82@gmail.com"
            type="button">
            <i class="bi bi-envelope icono_contacto"
              style="font-size: 30px;">
            </i>
          <a href="https://www.linkedin.com/in/raquel-casares-de-la-poza-9a363b25b/" target="_blank">
            <i
              class="bi bi-linkedin icono_contacto"
              style="font-size: 30px;">
            </i>
          </a>
        </div>

        <div class="w-75 d-flex pt-4 py-5 mb-5">
          <div class="w-50 py-4">
            <h1 class="TituloQuienSoy">Hola, me llamo</h1>
            <h1 class="TituloQuienSoy">Raquel Casares <i class="bi bi-code-slash"></i></h1>
            <h2 class="SubTitulosQuienSoy text-start">Junior Developer</h2>
            <p class="ParrafoQuienSoy text-start pe-5">
              Desarrolladora a tiempo completo, experta en el uso de diferentes
              tecnologías y gran apasionada de la programación.
            </p>

            <a href="#contacto">
              <button
                type="button"
                name="button"
                class="btn btn-primary p-3 me-3 SubTitulos"
                style="font-size: 0.9rem;">
                Contactame
                <i
                  class="bi bi-caret-right-fill ms-3"
                  style="font-size: 0.9rem;">
                </i>
              </button>
            </a>
            
            <a
            href="pdf/RAQUEL_CASARESDELAPOZA_CV.pdf"
            download
            rel="noopener noreferrer"
            target="_blank">
            <button
              type="button"
              name="button"
              class="btn btn-primary p-3 me-3 SubTitulos"
              style="font-size: 0.9rem">
              Descargar CV
              <i class="bi bi-download" style="font-size: 0.9rem"></i>
            </button>
          </a>
        
          </div>
          
          <div class="home_img" style="margin-top: -4%;">
            <div
              class="d-flex justify-content-center rounded-circle overflow-hidden circuloPerfilGrande" style="margin-left: 50%;">
              <img src="img/perfil.jpg" alt="" style="width: 230px;" />
            </div>
          </div>
        </div>
      </div>

      <!-- Habilidades -->
     
      <h2 class="TituloSecciones" id="habilidades"><u>Habilidades</u></h2>
      <div
        class="mx-5 py-5 d-flex justify-content-center"
        style="margin-top: 100px; margin-bottom: 100px">

        <!-- Desarrollo Frontend -->
        <div class="d-flex justify-content-center">
          <div class="skills__area">
            <h2 class="skills__title">Desarrollo Frontend</h2>

            <div class="skills__box">
              <div class="skills__group">
                <div class="skills__data">
                  <i
                    class="bi bi-patch-check"
                    style="color: var(--color-principal)"
                  ></i>

                  <div>
                    <h3 class="skills__name">HTML</h3>
                    <!-- <span class="skills__level">Intermedio</span> -->
                  </div>
                </div>

                <div class="skills__data">
                  <i
                    class="bi bi-patch-check"
                    style="color: var(--color-principal)"
                  ></i>

                  <div>
                    <h3 class="skills__name">CSS</h3>
                    <!-- <span class="skills__level">Intermedio</span> -->
                  </div>
                </div>

                <div class="skills__data">
                  <i
                    class="bi bi-patch-check"
                    style="color: var(--color-principal)">
                  </i>

                  <div>
                    <h3 class="skills__name">JavaScript</h3>
                    <!-- <span class="skills__level">Básico</span> -->
                  </div>
                </div>
              </div>

              <div class="skills__group">
                <div class="skills__data">
                  <i
                    class="bi bi-patch-check"
                    style="color: var(--color-principal)">
                  </i>

                  <div>
                    <h3 class="skills__name">Android</h3>
                    <!-- <span class="skills__level">Básico</span> -->
                  </div>
                </div>

                <div class="skills__data">
                  <i
                    class="bi bi-patch-check"
                    style="color: var(--color-principal)">
                  </i>

                  <div>
                    <h3 class="skills__name">Bootstrap</h3>
                    <!-- <span class="skills__level">Intermedio</span> -->
                  </div>
                </div>

                <div class="skills__data">
                  <i
                    class="bi bi-patch-check"
                    style="color: var(--color-principal)">
                  </i>

                  <div>
                    <h3 class="skills__name">GitHub</h3>
                    <!-- <span class="skills__level">Intermedio</span> -->
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- Desarrollo Backend -->

        <div class="d-flex justify-content-center">
          <div class="skills__area">
            <h2 class="skills__title">Desarrollo Backend</h2>

            <div class="skills__box">
              <div class="skills__group">
                <div class="skills__data">
                  <i
                    class="bi bi-patch-check"
                    style="color: var(--color-principal)">
                  </i>

                  <div>
                    <h3 class="skills__name">PHP</h3>
                    <!-- <span class="skills__level">Básico</span> -->
                  </div>
                </div>

                <div class="skills__data">
                  <i
                    class="bi bi-patch-check"
                    style="color: var(--color-principal)">
                  </i>

                  <div>
                    <h3 class="skills__name">MySQL</h3>
                    <!-- <span class="skills__level">Básico</span> -->
                  </div>
                </div>

                <div class="skills__data">
                  <i
                    class="bi bi-patch-check"
                    style="color: var(--color-principal)">
                  </i>

                  <div>
                    <h3 class="skills__name">Java</h3>
                    <!-- <span class="skills__level">Intermedio</span> -->
                  </div>
                </div>
              </div>

              <div class="skills__group">
                <div class="skills__data">
                  <i
                    class="bi bi-patch-check"
                    style="color: var(--color-principal)">
                  </i>

                  <div>
                    <h3 class="skills__name">JEE</h3>
                    <!-- <span class="skills__level">Intermedio</span> -->
                  </div>
                </div>

                <div class="skills__data">
                  <i
                    class="bi bi-patch-check"
                    style="color: var(--color-principal)">
                  </i>

                  <div>
                    <h3 class="skills__name">Apache</h3>
                    <!-- <span class="skills__level">Básico</span> -->
                  </div>
                </div>
                <div class="skills__data">
                  <i
                    class="bi bi-patch-check"
                    style="color: var(--color-principal)">
                  </i>

                  <div>
                    <h3 class="skills__name">MongoDB</h3>
                    <!-- <span class="skills__level">Básico</span> -->
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Sección Proyectos -->

      <h2 class="TituloSecciones" id="proyectos"><u>Proyectos</u></h2>
      <div
        class="mx-5 py-5 d-flex justify-content-center"
        style="margin-top: 100px; margin-bottom: 100px">
        <div class="d-flex justify-content-center" style="margin-inline: 2%">
          <div
            class="proyPeluditos d-flex flex-column "
            style="width: 500px; height: 250px"
          ></div>
          <div class="text-light position-absolute" style="margin-top: 18%;">
            <h4 class="SubTitulos" style="font-size: 1rem">Web Caninoterapia / Proyecto Integrado (DAW)</h4>
            <h3 class="Titulo">MiPeluditoSOS</h3>
            <a
            href="pdf/Proyecto Integrado-DAW-Raquel Casares De la Poza.pdf"
            download
            rel="noopener noreferrer"
            target="_blank">
            <button
              type="button"
              name="button"
              class="btn btn-primary rounded-pill">
              <i class="bi bi-link"></i>
            </button>
            </a>
          </div>
        </div>

        <div class="d-flex justify-content-center" style="margin-inline: 2%">
          <div
            class="proyComprasApp d-flex flex-column overflow-hidden"
            style="width: 500px; height: 250px">
          </div>
          <div class="text-light position-absolute" style="margin-top: 18%;">
            <h4 class="SubTitulos" style="font-size: 1rem">App Android / Proyecto Integrado (DAM)</h4>
            <h3 class="Titulo">MisComprasApp</h3>
            <a
            href="pdf/Proyecto Integrado-Raquel Casares De la Poza.pdf"
            download
            rel="noopener noreferrer"
            target="_blank">
            <button
              type="button"
              name="button"
              class="btn btn-primary rounded-pill">
              <i class="bi bi-link"></i>
            </button>
            </a>
          </div>
        </div>
      </div>
      <div
        class="mx-5 py-5 d-flex justify-content-center"
        style="margin-top: 100px; margin-bottom: 100px">
        <div class="d-flex justify-content-center" style="margin-inline: 2%">
          <div
            class="proyEgiptoWeb d-flex flex-column "
            style="width: 500px; height: 250px"
          ></div>
          <div class="text-light position-absolute" style="margin-top: 18%;">
            <h4 class="SubTitulos" style="font-size: 1rem">Web Egipto / Diseño de Interfaces Web (DAW)</h4>
            <h3 class="Titulo">EgiptoWeb</h3>
            <a
            href="https://66769bc1ff107b66af3e5048--statuesque-starlight-321dab.netlify.app/"
            
            rel="noopener noreferrer"
            target="_blank">
            <button
              type="button"
              name="button"
              class="btn btn-primary rounded-pill">
              <i class="bi bi-link"></i>
            </button>
            </a>
          </div>
        </div>

        <div class="d-flex justify-content-center" style="margin-inline: 2%">
          <div
            class="proyMyAvatar d-flex flex-column overflow-hidden"
            style="width: 500px; height: 250px">
          </div>
          <div class="text-light position-absolute" style="margin-top: 18%;">
            <h4 class="SubTitulos" style="font-size: 1rem">App Android / Programación Multimedia (DAM)</h4>
            <h3 class="Titulo">MyAvatar</h3>
            <a
            href="pdf/Práctica 4-PMDM-Raquel Casares De la Poza.pdf"
            download
            rel="noopener noreferrer"
            target="_blank">
            <button
              type="button"
              name="button"
              class="btn btn-primary rounded-pill">
              <i class="bi bi-link"></i>
            </button>
            </a>
          </div>
        </div>
      </div>
      
      <div
      class="mx-5 py-5 d-flex justify-content-center"
      style="margin-top: 100px; margin-bottom: 100px">
      <div class="d-flex justify-content-center" style="margin-inline: 2%">
        <div
          class="proyMiTiendecita d-flex flex-column "
          style="width: 500px; height: 250px"
        ></div>
        <div class="text-light position-absolute" style="margin-top: 18%;">
          <h4 class="SubTitulos" style="font-size: 1rem">App Web / Despliegue Aplicaciones Web (DAW)</h4>
          <h3 class="Titulo">MiTiendecita</h3>
          <a
          href="pdf/Práctica4-DAW-Raquel Casares De la Poza.pdf"
          download
          rel="noopener noreferrer"
          target="_blank">
          <button
            type="button"
            name="button"
            class="btn btn-primary rounded-pill">
            <i class="bi bi-link"></i>
          </button>
          </a>
        </div>
      </div>

      <div class="d-flex justify-content-center" style="margin-inline: 2%">
        <div
          class="proyProgramaGestion d-flex flex-column overflow-hidden"
          style="width: 500px; height: 250px">
        </div>
        <div class="text-light position-absolute" style="margin-top: 18%;">
          <h4 class="SubTitulos" style="font-size: 1rem">App Escritorio / Programación - Java</h4>
          <h3 class="Titulo">Programa Gestión Autoescuela</h3>
          <a
          href="pdf/Programación 2-Manual Usuario-Raquel Casares De la Poza.pdf"
          download
          rel="noopener noreferrer"
          target="_blank">
          <button
            type="button"
            name="button"
            class="btn btn-primary rounded-pill">
            <i class="bi bi-link"></i>
          </button>
          </a>
        </div>
      </div>
    </div>
    
    <!-- Sección Experiencia -->

    <h2 class="TituloSecciones" id="experiencia"><u>Experiencia y Cursos</u></h2>
    <div class="mx-5 py-5 d-flex justify-content-center" style="margin-top: 100px; margin-bottom: 100px">
     
      <div class="d-flex justify-content-center" style="margin-inline: 2%">
        <div class="card" style="width: 18rem;">
          <img src="./img/Expe&Cursos/Diploma_Git.png" class="card-img-top" alt="Diploma Curso Git">
          <div class="card-body" style="background-color: #9e36e1;">
            <h5 class="card-title">Git</h5>
            <p class="card-text">Open Webinars
            </p>
            <a href="#" class="btn btn-primary">Go</a>
          </div>
        </div>
      </div>

      <div class="d-flex justify-content-center" style="margin-inline: 2%">
        <div class="card" style="width: 18rem;">
          <img src="./img/Expe&Cursos/Imagen7.png" class="card-img-top" alt="IHP Cita Previa">
          <div class="card-body" style="background-color: #eb10ff">
            <h5 class="card-title">Página Cita Previa</h5>
            <p class="card-text">Instituto Hispalense de Pediatría</p>
            <a href="#" class="btn btn-primary">Go</a>
          </div>
        </div>
      </div>

      <div class="d-flex justify-content-center" style="margin-inline: 2%">
        <div class="card" style="width: 18rem;">
          <img src="./img/Expe&Cursos/Imagen8.png" class="card-img-top" alt="IHP Equipos">
          <div class="card-body" style="background-color: rgb(249, 160, 215);">
            <h5 class="card-title">Aplicación Equipos</h5>
            <p class="card-text"><b>Instituto Hispalense de Pediatría</b></p>
            <a href="#" class="btn btn-primary">Go</a>
          </div>
        </div>
      </div>







    </div>
      <!-- Sección Contacto -->

      <h2 class="TituloSecciones" id="contacto"><u>Contacto</u></h2>
      <div
        class="mx-5 py-4 d-flex justify-content-center"
        style="margin-top: 100px; margin-bottom: 100px">
        <div class="d-flex grid">
          <div class="justify-content-center py-5 mt-2">

            <!-- Correo -->
            <div class="d-flex grid mb-3">
              <a
            href="mailto:raquelcasares82@gmail.com"
            type="button"
            class="btn btn-outline-primary ms-1">
            <i class="bi bi-envelope"></i>
            <div class="d-block">
              <h3 class="Titulo">Correo</h3>
              <span class="SubTitulos">raquelcasares82@gmail.com</span>
            </div>
          </a>
            </div>
 
            <!-- Teléfono -->
            <div class="d-flex grid mb-3 btn btn-outline-primary ms-1">
              <i class="bi bi-telephone"></i>

              <div class="d-block">
                <h3 class="Titulo">Teléfono</h3>
                <span class="SubTitulos">653093439</span>
              </div>
            </div>

            <!-- Ubicación -->
            <div class="d-flex grid btn btn-outline-primary ms-1">
              <i class="bi bi-geo-alt"></i>

              <div class="d-block">
                <h3 class="Titulo">Ubicación</h3>
                <span class="SubTitulos">España</span>
              </div>
            </div>
          </div>
          <div> 

            <!-- Imagen-Blog -->
          <div
            class="proyBlog d-flex flex-column "
            style="width: 550px; height: 370px">
          </div>
      </div>
        </div>
      </div>
      
    </section>
<!-- ======== "Pie" de página ======== -->
<div class="d-flex justify-content-center">
  <p class="text-light SubTitulos">
    · © 2024 Raquel Casares De la Poza ·
  </p>
</div>
     
    <!-- ======== Cierre para tablets y Pantallas grandes lg ======== -->

    <!-- JavaScript with Popper -->
    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-A3rJD856KowSb7dwlZdYEkO39Gagi7vIsF0jrRAoQmDKKtQBHUuLZ9AsSv4jD4Xa"
      crossorigin="anonymous">
    </script>

  </body>
</html>


















Here are some ideas to get you started:


- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
