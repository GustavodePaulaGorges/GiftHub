<template>
  <div class="ContainerOfertas">
    <div id="CarouselOfertas" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img
            src="@/imgs/Carousel1.png"
            class="carouselImg"
            alt="..."
          />
        </div>
        <div class="carousel-item">
          <img
            src="@/imgs/Carousel2.png"
            class="carouselImg"
            alt="..."
          />
        </div>
        <div class="carousel-item">
          <img
            src="@/imgs/Carousel3.png"
            class="carouselImg"
            alt="..."
          />
        </div>
      </div>
      <button
        class="carousel-control-prev"
        type="button"
        data-bs-target="#CarouselOfertas"
        data-bs-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button
        class="carousel-control-next"
        type="button"
        data-bs-target="#CarouselOfertas"
        data-bs-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
  </div>
</template>
