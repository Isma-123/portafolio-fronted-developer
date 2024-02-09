# portafolio-fronted-developer
portafolio-fronted-developer

<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Desarrollo Web Fronted</title>
     <meta name="portafolio" content="HTML, CSS, Javascript, React">
     <meta name="viewport" content="width=device-width, initial-scale=1">
     <link rel="preconnect" href="https://fonts.googleapis.com">
     <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
     <link href="https://fonts.googleapis.com/css2?family=Honk&display=swap" rel="stylesheet">
     <link rel="stylesheet" href="style.css">
     <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
  </head>
  <style>
    /* Estilos generales */
.hero-imagen-desarrollador { 
    width: 200px;
    height: 200px;
    border-radius: 50%;
    margin: 20px;
}

.hero-principal h2 {
    font-size: 1.5rem;
    color: gray;
}


.texto-blanco { 
    color: white    ;
}

.hero-principal { 
    padding: 3rem;
}

section { 
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

.Seccion-titulo { 
    font-size: 5pc;
    padding: 15px 0px   ;
    font-family: 'Honk',system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}


h1 {
    font-size: 2.5rem;
    font-family: 'Honk', system-ui;
} 

.Seccion-oscura { 
    background-color: black;
    color: white;
}

/* 
Experiencia */

.Experiencia {
    padding: 40px 40px 60px 40px;
}

.Experiencia .columna { 
    border: 2px solid #808080;
    padding: 50px;
    margin: 12px 0;
    align-items: center;
    justify-content: space-evenly;
    flex-direction: column;
   transition-duration: 2s;
   cursor: pointer;
} 

.Experiencia .columna:hover {
 transition-duration: 2s;
 color: white;
 background-color: black;
}



.seccion-clara { 
    color: black;
    gap: 50px;
   
} 

.experiencia-titulo { 
    font-size: 25px;
    font-weight: bold;
    margin: 15px 0px;
    font-family: 'Honk', system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}


.img-icon { 
    font-size: 1.5rem;
    padding: 8px 10px;
}
/* sobre mi  */ 

.sobre-mi { 
    height: 500px;
    padding: 10px;
}

.sobre-mi .contenedor { 
    max-width: 600px;
    text-align: center;
}
/* seccion hero  */

.hero { 
 background-color: #f5f6f7;
 min-height: 450px;
 text-align: center;
}

/* Barra de navegacion */

.navbar { 
    padding: 2rem;
    background-color: #f5f6f7;
}

.navbar-collapse { 
    align-items: center;
    justify-content: space-between;
}
/* adatable resposivo */

@media screen and (max-width: 767px) {
    .navbar-brand { 
        display: none;
    }
}

@media screen and (min-width: 700px) { 
 .hero-inferior-imagen { 
    max-width: 600px;
 }
}

/* Proyectos  */ 


.proyectos-recientes img { 
    height: 100%;
    width: 100%;
    padding: 10px;
    border-radius: 10px;
    display: block;
    transition: all 0.2s ease;
    cursor: pointer;
} 

.proyectos-contenedor {
  padding-top: 60px;
  margin-bottom: 40px;
}

.overlay {
    transition: all 0.2s ease;
    opacity: 0;
    position: absolute;
    top: 50%;
    left: 50px;
    transform: translate(-50% -50%);
    text-align: center;
}

.overlay p { 
    
    font-size: 25px;
    font-weight: bold;
    margin-bottom: 0;
}

.proyecto {
 position: relative;
}


.proyecto:hover img { 
    opacity: 0.2;
}

.overlay:hover .overlay {
  
    opacity: 1;
}

/* 
Codigos Botones  */ 

.shadow__btn {
    padding: 10px 20px;
    border: none;
    font-size: 17px;
    color: #fff;
    border-radius: 7px;
    letter-spacing: 4px;
    font-weight: 700;
    text-transform: uppercase;
    transition: 0.5s;
    transition-property: box-shadow;
  }
  
  .shadow__btn {
    background: rgb(0,140,255);
    box-shadow: 0 0 25px rgb(0,140,255);
  }
  
  .shadow__btn:hover {
    box-shadow: 0 0 5px rgb(0,140,255),
                0 0 25px rgb(0,140,255),
                0 0 50px rgb(0,140,255),
                0 0 100px rgb(0,140,255);
  }


    

  </style>
  <body>
 <!-- barra de navegacion -->
 <nav class="navbar navbar-expand-md navbar-light">
  <div class="container-fluid">
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo01" aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbar-troggler">
      <a class="navbar-brand" href="#">
        <img src="favicon icon.webp" width="50"   alt="Logo de la pagina">
      </a>
      <ul class="navbar-nav d-flex justify-content-center align-items-ceneter">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Sobre mi</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Proyectos</a>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled" aria-disabled="true">Testimonio</a>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled" aria-disabled="true">Contactos</a>
        </li>
      </ul>
    </div>
  </div>
</nav>

<!-- Seccion hero  -->
   <section class="hero align-items-stretch">
      <div class="hero principal d-flex flex-column justify-content-center align-items-center">
        <img class="hero-imagen-desarrollador" src="person-circle.svg" alt="FotodeAbdias">
        <h1 id="cambiodeText">Hola Soy Abdias Feliz!</h1>
        <script>
         const textos = ["Bienvenidos", "Hola Soy Abdias Feliz"];
           let indice = 0;

setInterval(() => {
  document.getElementById('cambiodeText').innerText = textos[indice];
  indice = (indice + 1) % textos.length;
}, 3000);

        </script>
        <h2>Desarrollo Web Mi portafolio como Fronted-developer</h2>
      </div>
      <div class="hero-inferior">
        <img class="hero-inferior-imagen img-fluid"  width="50%f"   src="proyecto web.svg" alt="Monitor, laptop css, react, Javascript">
       </div>
   </section>
  <!-- Sobre Mi -->
   <section class="sobre-mi Seccion-oscura">
    <div class="contenedor">
      <h2 class="Seccion-titulo texto-blanco">Conoce a Abdias</h2>
       <p class="seccion-texto">Hola! a todos soy un apacionado Programador web que le gusta colaborar soy extrovertido me gusta la paz me gusta estar solo, Quiero ser mejor cada dia tambien, Por ahora los dejare con eso Aprender mas tecnolgias cada dia mas Los Quiero!</p>
    </div>
   </section>

   <!-- Experiencia -->
   <Section class="Experiencia seccion-clara">
      <div class="container text-center">
        <div class="row">
           <!-- Desarrollo-web -->
           <div class="columna col-12 col-md-4">
             <img class="img-icon" width="25%" src="laptop.svg" alt="foto laptop">
              <p class="experiencia-titulo">Desarrollo-Web</p>
              <p>Estas son cada una de mis experiencia en el ambito de desarrollo Aqui vamos!</p>
              <button class="shadow__btn">
                Ver!
            </button> 
           </div>
            <div class="columna col-12 col-md-4">
              <img class="img-icon" width="25%" src="laptop.svg" alt="foto laptop">
              <p class="experiencia-titulo">Cursos</p>
              <p>Lista de curso Realizados puedes visitarlos todos aqui.</p>  
              <button class="shadow__btn">
                Ver!
            </button> 
            </div>
            <div class="columna col-12 col-md-4">
              <img class="img-icon" width="25%" src="laptop.svg" alt="foto laptop">
               <p class="experiencia-titulo">Mis estudios</p>
                 <p>Aqui le mostrare los link donde pueden ir a praticar codigo!</p>
                 <button class="shadow__btn">
                  Ver!
              </button> 
               </div>
            </div>
        </div>

      </div>
   </Section>
   <section class="proyectos-recientes seccion-clara d-flex flex-column">
    <h2 class="Seccion-titulo texto-negro">Mis Proyectos mas recientes</h2>
      <h3 class="seccion-descripcion">Estos son algunos de mis proyectos</h3>
        <!-- galeria  -->
         <div class="container text-center proyectos-contenedor">
          <div class="row">
             <div class="col 12 col-md-6 col-lg-4">
             <div class="proyecto">
              <img src="pratica progrmacion.avif" alt="Proyecto1">
              <div class="overlay">
                <p>Proyecto1</p>
              </div>
             <div class="iconos contenedor">
              <a href="https://github.com/Isma-123/portafolio-fronted-developer" target="_blank" rel="noopener noreferrer "><i class="bi bi-github">Hola</i></a>
              
              </div>
             </div>
             </div>

          </div>
         </div>

   </section>
   
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>
  </body>
  </html>
