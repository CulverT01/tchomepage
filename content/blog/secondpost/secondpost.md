---
title: Pulling the website by its Bootstraps.
description: Evidencing the use of the bootstrap framework on the website.
date: 2023-12-27
tags:
  - bootstrap
  - web skill evidence
---
<div class="container fluid">
  <h1 class="col align-self-center">Pulling the website by its Bootstraps</h1>
  <div class="row justify-content-center">
    <p class="col-8">
    This post evidences the usage of Bootstrap across the website. Bootstrap is a framework that's used to give styling to your website as well as allow it be dynamic with various components like the Carousel shown below. The cards that are shown are from Yu-Gi-Oh! trading card game that I own.
    </p>
  </div>
  <div class="row justify-content-center">
    <div class="col-6">
      <div id="carouselCaptions" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <p><img src="ysyr-en001.JPG" alt="Dark Magician"></p>
            <div class="carousel-caption d-none d-md-block">
              <h5 class="text-info">Dark Magician</h5>
              <p class="text-info">The ultimate wizard in terms of attack and defence.</p>
            </div>
          </div>
          <div class="carousel-item">
            <p><img src="yskr-en001.JPG" alt="Blue-Eyes White Dragon"></p>
            <div class="carousel-caption d-none d-md-block">
              <h5 class="text-info">Blue-Eyes White Dragon</h5>
              <p class="text-info">This legendary dragon is a powerful engine of destruction. <br/>
              Virtually invincible, very few have faced this awesome creature and lived to tell the tale.</p>
            </div>
          </div>
          <div class="carousel-item">
            <p><img src="hac1-en003.jpg" alt="Red-Eyes Black Dragon"></p>
            <div class="carousel-caption d-none d-md-block">
              <h5 class="text-info">Red-Eyes Black Dragon</h5>
              <p class="text-info">A ferocious dragon with a deadly attack.</p>
            </div>
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselCaptions" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselCaptions" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
    </div>
</div>



