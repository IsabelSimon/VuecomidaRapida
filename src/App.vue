<template>
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Comida Rápida - Isabel Cristina Simón Morales 10° A</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Comidas</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Bebidas</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Postres</a>
        </li>
        
      </ul>
    </div>
  </div>
  </nav>
  <hr>
  <div class="container">
    <div class="text-center mb-3"> <h4>Comida corrida de hoy</h4></div>
   
    <div class="row">
      <div class="col-md-4 ">
        <div class="card" style="width: 18rem;">
          <imagen>
            <img src="https://cdn.pixabay.com/photo/2015/04/08/13/13/food-712665_960_720.jpg" class="card-img-top" alt="...">
          </imagen>
          <div class="card-body text-center">
            <h5 class="card-title">Comida con carne</h5>
            <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc ut sapien malesuada.</p>
            <a href="#" class="btn btn-primary">$110</a>
          </div>
        </div>      
      </div>
      <div class="col-md-4">
        <div class="card" style="width: 18rem;">
          <imagen>
            <img src="https://cdn.pixabay.com/photo/2017/12/10/14/47/pizza-3010062_960_720.jpg" class="card-img-top" alt="...">
          </imagen>
          <div class="card-body text-center">
            <h5 class="card-title">Pizza Vegana</h5>
            <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc ut sapien malesuada.</p>
            <a href="#" class="btn btn-primary">$420</a>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card" style="width: 18rem;">
          <imagen>
            <img src="https://cdn.pixabay.com/photo/2016/09/15/19/24/salad-1672505_960_720.jpg" class="card-img-top" alt="...">
          </imagen>
          <div class="card-body text-center">
            <h5 class="card-title">Ensalada de la casa</h5>
            <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc ut sapien malesuada.</p>
            <a href="#" class="btn btn-primary">$130</a>
          </div>
        </div>
      </div>
        
    </div>
    <div class="row  mt-3">
      <div class="col-md-4">
        <div class="card" style="width: 18rem;">
          <imagen>
            <img src="https://cdn.pixabay.com/photo/2017/12/09/08/18/pizza-3007395_960_720.jpg" class="card-img-top" alt="...">
          </imagen>
          <div class="card-body text-center">
            <h5 class="card-title">Pizza con mariscos</h5>
            <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc ut sapien malesuada.</p>
            <a href="#" class="btn btn-primary">$510</a>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card" style="width: 18rem;">
          <imagen>
            <img src="https://cdn.pixabay.com/photo/2018/04/13/17/14/vegetable-skewer-3317060_960_720.jpg" class="card-img-top" alt="...">
          </imagen>
          <div class="card-body text-center">
            <h5 class="card-title">Brochetas saludables</h5>
            <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc ut sapien malesuada.</p>
            <a href="#" class="btn btn-primary">$85</a>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card" style="width: 18rem;">
          <imagen>
            <img src="https://cdn.pixabay.com/photo/2014/12/15/13/40/croissants-569075_960_720.jpg" class="card-img-top" alt="...">
          </imagen>
          <div class="card-body text-center">
            <h5 class="card-title">Cuernitos con mermelada</h5>
            <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc ut sapien malesuada.</p>
            <a href="#" class="btn btn-primary">$75</a>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="black">
    <div class="row">
      <div class="col-md-6">
        <p>Encuentranos en: Privada 9 de marzo #510 local 3</p>
        <p>Teléfono: +55 2381698532</p>
        <p>Email: comidarapida@crsimon.com</p>
      </div>
      <div class="col-md-3">
        <p>Nuestras bebidas</p>
        <p>Nuestras comidas</p>
        <p>Bienvenida la temprada</p>
      </div>
      <div class="col-md-3">
        <p>Menús para eventos especiales</p>
        <p>Nuestros platillos especiales</p>
      </div>
    </div>
  </div>
  
    
  
</template>
<style>
  .black{
    margin-top: 2em;
    background-color: black;
    color: lightgray;
    padding: 4em;
  }
</style>
<script>
import Imagen from "./components/Image.vue"
 export default {
   components: {Imagen,}, 
 };

</script>