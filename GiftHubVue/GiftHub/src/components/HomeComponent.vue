<script>
import CarouselOfertas from "@/components/contents/CarouselOfertas.vue";
export default {
  components: { CarouselOfertas },
};
</script>
<template>
  <CarouselOfertas />
  <div class="container cardcontainer">
    <div class="row">
      <div class="col">
        <div class="card cardLojas">
          <img
            src="@/imgs/Loja1.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Eu quero Presentes</h5>
            <p class="card-text">Loja de presentes infantis</p>
            <a href="#" class="btn btn-primary">Acessar</a>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card cardLojas">
          <img
            src="@/imgs/loja2.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">BIRUTA</h5>
            <p class="card-text">Presentes variados</p>
            <a href="#" class="btn btn-primary">Acessar</a>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card cardLojas">
          <img
            src="@/imgs/loja3.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Empório Criativo</h5>
            <p class="card-text">Empório de presentes</p>
            <a href="#" class="btn btn-primary">Acessar</a>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card cardLojas">
          <img
            src="@/imgs/loja4.jpg"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title">Presentes Criativos</h5>
            <p class="card-text">Presentes criativos</p>
            <a href="#" class="btn btn-primary">Acessar</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
