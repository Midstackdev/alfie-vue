<template>
  <main>
    <section class="container blog-posts">
      <h1 class="heading">Articles</h1>
      <div class="popular-posts flex-wrap align-center justify-center">
        <div class="post">
          <picture>
            <source type="image/webp" srcset="@/assets/images/Image-4.webp" />
            <source type="image/png" srcset="@/assets/images/Image-4.png" />
            <img
              src="@/assets/images/Image-4.png"
              alt="popular blog post image"
            />
          </picture>
          <!-- <img src="@/assets/images/Image-4.webp" alt="popular blog post image"> -->
          <h3 class="headline">The Founder</h3>
          <p class="post-summary">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            Voluptates, est.
          </p>
          <a class="read-more">
            Read More
            <span class="arrow"> &#x2192;</span>
          </a>
        </div>
        <div class="post">
          <picture>
            <source type="image/webp" srcset="@/assets/images/Image-5.webp" />
            <source type="image/png" srcset="@/assets/images/Image-5.png" />
            <img
              src="@/assets/images/Image-5.png"
              alt="popular blog post image"
            />
          </picture>
          <!-- <img src="@/assets/images/Image-5.webp" alt="popular blog post image"> -->
          <h3 class="headline">The CEO</h3>
          <p class="post-summary">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            Voluptates, est.
          </p>
          <a class="read-more">
            Read More
            <span class="arrow"> &#x2192;</span>
          </a>
        </div>
      </div>
    </section>
  </main>
</template>