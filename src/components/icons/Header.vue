<template>
    <nav class="navbar navbar-expand-lg my-4 ">
      <div class="container">
        <a class="navbar-brand col-4" href="#"> Colégio Interagir</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse col-5" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Início</a>
            </li>
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                Sobre nós
              </a>
              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">Estrutura</a></li>
                <li><a class="dropdown-item" href="#">Equipe</a></li>
                <li><a class="dropdown-item" href="#">Nossa Historia</a></li>
              </ul>
            </li>
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                Segmentos 
              </a>
              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">Educação Infantil</a></li>
                <li><a class="dropdown-item" href="#">Ensino Fundamental I</a></li>
                <li><a class="dropdown-item" href="#">Ensino Fundamental II</a></li>
              </ul>
            </li>

            <li class="nav-item">
              <a class="nav-link" href="#">Interagindo</a>
            </li>
          </ul>
          <ul class="navbar-nav">
            <li class="nav-item" > 
              <a class="btn btn-outline-success mx-1">Agendar Visita</a>
              <a class="btn btn-success">Portal</a>
            </li>
          </ul>
        </div>
        <div>
          
        </div>
      </div>
    </nav>
</template>
<style scoped>
  .img-resize {
     width: 2em; /* ou qualquer outro valor desejado */
     height: auto; /* Isso manterá a proporção original da imagem */
  }
  .my-4{
    z-index:3;
  }
</style>