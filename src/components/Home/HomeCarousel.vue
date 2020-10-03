<template>
  <main>
    <div class="carousel banner" id="homepage">
      <div class="arrows">
        <span class="icon button left" n="0">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 53 53">
            <g transform="translate(-0.348)">
              <rect
                class="a"
                width="53"
                height="53"
                transform="translate(0.348)"
              />
              <path
                class="b"
                d="M36.421,50.093l2.219-2.219L17.189,26.421,38.641,4.969,36.421,2.75,12.75,26.421Z"
                transform="translate(0.814 0.176)"
              />
              <rect
                class="a"
                width="53"
                height="53"
                transform="translate(0.348)"
              />
            </g>
          </svg>
        </span>
        <span class="icon button right" n="1">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 53 53">
            <g transform="translate(53 53) rotate(180)">
              <rect class="a" width="53" height="53" />
              <path
                class="b"
                d="M23.671,47.343l2.219-2.219L4.439,23.671,25.891,2.219,23.671,0,0,23.671Z"
                transform="translate(13.213 2.715)"
              />
              <rect class="a" width="53" height="53" />
            </g>
          </svg>
        </span>
      </div>
      <div class="carousel-container">
        <div class="content flex align-center justify-center active">
          <picture>
            <source
              type="image/webp"
              srcset="@/assets/images/alfie-home-cover.webp"
            />
            <source
              type="image/jpeg"
              srcset="@/assets/images/alfie-home-cover.jpeg"
            />
            <img
              src="@/assets/images/alfie-home-cover.jpeg"
              alt="banner image"
            />
          </picture>
          <div class="info flex align-center justify-center">
            <h4 class="caption">We Define Fashion in Africa and Beyond</h4>
          </div>
        </div>
        <div class="content flex align-center justify-center">
          <picture>
            <source
              type="image/webp"
              srcset="@/assets/images/alfie-home-cover-2.webp"
            />
            <source
              type="image/jpeg"
              srcset="@/assets/images/alfie-home-cover-2.jpeg"
            />
            <img
              src="@/assets/images/alfie-home-cover-2.jpeg"
              alt="banner image"
            />
          </picture>
          <div class="info flex align-center justify-center">
            <h4 class="caption">We offer quality in masses</h4>
          </div>
        </div>
        <div class="content flex align-center justify-center">
          <picture>
            <source
              type="image/webp"
              srcset="@/assets/images/alfie-home-cover-3.webp"
            />
            <source
              type="image/jpeg"
              srcset="@/assets/images/alfie-home-cover-3.jpeg"
            />
            <img
              src="@/assets/images/alfie-home-cover-3.jpeg"
              alt="banner image"
            />
          </picture>
          <div class="info flex align-center justify-center">
            <h4 class="caption">We are the definition of fashion</h4>
          </div>
        </div>
      </div>
      <div class="indicator-bars flex justify-center">
        <span class="bar active"></span>
        <span class="bar"></span>
        <span class="bar"></span>
      </div>
    </div>
  </main>
</template>