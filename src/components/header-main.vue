<template>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container">
      <a class="navbar-brand" href="#">Possani's Store</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Carrinho</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              Matérias
            </a>
            <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
              <li><a class="dropdown-item" href="#">Álgebra</a></li>
              <li><a class="dropdown-item" href="#">Geometria Analítica</a></li>
              <li><hr class="dropdown-divider"></li>
              <li><a class="dropdown-item" href="#">Matérias Novas!</a></li>
            </ul>
          </li>
          <li>
            <a href="#"><img src="https://placekitten.com/300/300" class="imagem"></a>
            
          </li>
        </ul>
        <form class="d-flex">
          <input class="form-control me-3" type="search" placeholder="Pesquisar" aria-label="Search">
          <button class="btn btn-outline-success" type="submit">Ok</button>
        </form>
      </div>
    </div>
  </nav>
</template>


<style>
.nav-item{
  padding-top: 30px;
}
.imagem{
  margin-left: 10px;
  height: 100px;
  border-radius: 50%;
  padding: 10px;
}
.navbar-brand{
  font-weight: bolder;
  font-size: x-large;
}
</style>