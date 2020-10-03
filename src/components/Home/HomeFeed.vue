<template>
  <div>
    <section class="highlight">
      <div class="container main flex-wrap justify-center align-center">
        <picture>
          <source type="image/webp" srcset="@/assets/images/nest.webp" />
          <source type="image/png" srcset="@/assets/images/nest.png" />
          <img src="@/assets/images/nest.png" alt="nest logo" />
        </picture>
        <!-- <img src="@/assets/images/nest.webp" alt="nest logo"> -->
        <div class="info">
          <h2 class="title">A Nest Community Member</h2>
          <p class="subtext">
            <span class="emphasis name">Alfie Designs</span> is a proud member
            of the Nest Artisan Guild, a global community of more than 500
            artisan businesses praticing diverse craftmanship across nearly 100
            nations. In partnership with Nest, a non-profit 501(c)3, we are
            working towards a more inclusive global economy that brings
            increased opportunity to our artisans, their families, and our
            communities. To learn more, please visit
            <a href="https://www.buildanest.org" class="emphasis"
              >www.buildanest.org</a
            >
          </p>
        </div>
      </div>
    </section>
    <section class="clients-feedback">
      <h1 class="heading">What our clients say</h1>
      <div class="feedback-container">
        <!-- buttons and indicators will be absolutely positioned -->
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
        <!-- start of client feedbacks -->
        <div class="mention flex-column align-center" id="m-0">
          <p class="feedback-text">
            Lorem, ipsum dolor sit amet consectetur, adipisicing elit. Impedit
            laboriosam laborum veniam unde voluptate perspiciatis.
          </p>
          <div class="client-info flex align-center">
            <picture>
              <source type="image/webp" srcset="@/assets/images/Image-6.webp" />
              <source type="image/png" srcset="@/assets/images/Image-6.png" />
              <img
                class="photo"
                src="@/assets/images/Image-6.png"
                alt="client image"
              />
            </picture>
            <div class="details">
              <p class="name">John Doe</p>
              <p class="company">ABC Company Limited</p>
            </div>
          </div>
        </div>
        <div class="all-feedbacks">
          <!-- when either buttons are clicked, a new feedback will be fetched from this container -->
          <div class="flex-column align-center" id="cf-0">
            <p class="feedback-text">
              Lorem, ipsum dolor sit amet consectetur, adipisicing elit. Impedit
              laboriosam laborum veniam unde voluptate perspiciatis.
            </p>
            <div class="client-info flex align-center">
              <picture>
                <source
                  type="image/webp"
                  srcset="@/assets/images/Image-6.webp"
                />
                <source type="image/png" srcset="@/assets/images/Image-6.png" />
                <img
                  class="photo"
                  src="@/assets/images/Image-6.png"
                  alt="client image"
                />
              </picture>
              <!-- <img src="@/assets/images/Image-6.webp" alt="client image" class="photo"> -->
              <div class="details">
                <p class="name">John Doe</p>
                <p class="company">ABC Company Limited</p>
              </div>
            </div>
          </div>
          <div class="flex-column align-center" id="cf-1">
            <p class="feedback-text">
              Lorem, ipsum dolor sit amet consectetur, adipisicing elit. Impedit
              laboriosam laborum veniam unde voluptate perspiciatis.
            </p>
            <div class="client-info flex align-center">
              <picture>
                <source type="image/webp" srcset="@/assets/images/ceo.webp" />
                <source type="image/png" srcset="@/assets/images/ceo.png" />
                <img
                  class="photo"
                  src="@/assets/images/ceo.png"
                  alt="client image"
                />
              </picture>
              <!-- <img src="@/assets/images/ceo.webp" alt="client image" class="photo"> -->
              <div class="details">
                <p class="name">Ruby Roundhouse</p>
                <p class="company">XYZ Inc</p>
              </div>
            </div>
          </div>
          <div class="flex-column align-center" id="cf-2">
            <p class="feedback-text">
              Lorem, ipsum dolor sit amet consectetur, adipisicing elit. Impedit
              laboriosam laborum veniam unde voluptate perspiciatis.
            </p>
            <div class="client-info flex align-center">
              <picture>
                <source
                  type="image/webp"
                  srcset="@/assets/images/Image-4.webp"
                />
                <source type="image/png" srcset="@/assets/images/Image-4.png" />
                <img
                  class="photo"
                  src="@/assets/images/Image-4.png"
                  alt="client image"
                />
              </picture>
              <!-- <img src="@/assets/images/Image-4.webp" alt="client image" class="photo"> -->
              <div class="details">
                <p class="name">Angela Ashton</p>
                <p class="company">Milky Productions</p>
              </div>
            </div>
          </div>
          <div class="flex-column align-center" id="cf-3">
            <p class="feedback-text">
              Lorem, ipsum dolor sit amet consectetur, adipisicing elit. Impedit
              laboriosam laborum veniam unde voluptate perspiciatis.
            </p>
            <div class="client-info flex align-center">
              <picture>
                <source
                  type="image/webp"
                  srcset="@/assets/images/products/men/alfie-m4.webp"
                />
                <source
                  type="image/png"
                  srcset="@/assets/images/products/men/alfie-m4.png"
                />
                <img
                  class="photo"
                  src="@/assets/images/products/men/alfie-m4.png"
                  alt="client image"
                />
              </picture>
              <!-- <img src="@/assets/images/products/men/alfie-m4.webp" alt="client image" class="photo"> -->
              <div class="details">
                <p class="name">Jason Woods</p>
                <p class="company">Woodin</p>
              </div>
            </div>
          </div>
        </div>
        <!-- end of feedbacks -->
        <div class="indicator-bars flex justify-center">
          <span class="bar active"></span>
          <span class="bar"></span>
          <span class="bar"></span>
          <span class="bar"></span>
        </div>
      </div>
    </section>
  </div>
</template>