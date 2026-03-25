---
cascade:
- _target:
    kind: page
  params:
    show_breadcrumb: true
sections:
- block: markdown
  design:
    columns: 1
  content:
    text: |
      When I am not doing mathematics, I can often be found running, climbing, cycling, hiking, and birdwatching.
    
      Check out [my flickr](https://www.flickr.com/photos/203778738@N06/) for more of my wildlife photos.
      
      <!--<figure style="text-align: center; margin: 20px auto;">
        <img src="/images/lake.jpg" alt="Lake view" style="display: block; margin: 20px auto; max-width:80%; border-radius:10px;">
        <figcaption style="font-size:0.9em; color:#555; margin-top:5px;">W&ouml;rthersee from the Pyramidenkogel.</figcaption>
      </figure>-->
      
      <div class="swiper">
        <div class="swiper-wrapper">
          <div class="swiper-slide">
            <img src="/images/Schladming-1.jpg" alt="Photo 1">
            <p>Schladming, Austria</p>
          </div>
          <div class="swiper-slide">
            <img src="/images/sandhill-crane-1.jpg" alt="Photo 2">
            <p>Sandhill cranes</p>
          </div>
          <div class="swiper-slide">
            <img src="/images/hoary-marmot-1.jpg" alt="Photo 3">
            <p>Hoary marmot</p>
          </div>
          <div class="swiper-slide">
            <img src="/images/Schoberpass-1.jpg" alt="Photo 4">
            <p>Schoberpass, Austria</p>
          </div>
          <div class="swiper-slide">
            <img src="/images/red-faced-warbler-1.jpg" alt="Photo 5">
            <p>Red-faced warbler</p>
          </div>
          <div class="swiper-slide">
            <img src="/images/plitvice-lakes-1.jpg" alt="Photo 6">
            <p>Plitviče Lakes, Croatia</p>
          </div>
        </div>
        <div class="swiper-button-next"></div>
        <div class="swiper-button-prev"></div>
      </div>
      
      <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@10/swiper-bundle.min.css" />
      <style>
      .swiper {
        width: 100%;
        max-width: 800px;
        margin: 1rem auto;
      }
      .swiper-slide {
        display: flex;
        flex-direction: column;
        align-items: center;
      }
      .swiper-slide img {
        width: 100%;
        max-width: 800px;
        height: auto;
        display: block;
        margin: 0 auto;
        border-radius: 8px;
      }
      .caption {
        text-align: center;
        font-size: 0.9rem;
        margin-top: 0.5rem;
        padding: 0 0.5rem;
      }
      @media (max-width: 600px) {
        .caption {
          font-size: 0.8rem;
        }
        .swiper-button-next,
        .swiper-button-prev {
          display: none;
        }
      }
      </style>
      
      <script src="https://cdn.jsdelivr.net/npm/swiper@10/swiper-bundle.min.js"></script>
      <script>
      new Swiper('.swiper', {
        loop: true,
        navigation: {
          nextEl: '.swiper-button-next',
          prevEl: '.swiper-button-prev',
        },
        pagination: {
          el: '.myGallery .swiper-pagination',
          clickable: true,
        },
      });
      </script>
  id: miscellaneous
summary: Miscellaneous
title: Miscellaneous
type: landing
---