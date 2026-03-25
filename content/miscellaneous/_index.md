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
            <img src="/images/Schladming-1.jpg" alt="schladming-1">
            <p>Schladming, Austria</p>
          </div>
          <div class="swiper-slide">
            <img src="/images/sandhill-crane-1.jpg" alt="sandhill-cranes-1">
            <p>Sandhill cranes</p>
          </div>
          <div class="swiper-slide">
            <img src="/images/hoary-marmot-1.jpg" alt="hoary-marmot-1">
            <p>Hoary marmot</p>
          </div>
          <div class="swiper-slide">
            <img src="/images/Schoberpass-1.jpg" alt="schoberpass-1">
            <p>Schoberpass, Austria</p>
          </div>
          <div class="swiper-slide">
            <img src="/images/red-faced-warbler-1.jpg" alt="red-faced-warbler-1">
            <p>Red-faced warbler</p>
          </div>
          <div class="swiper-slide">
            <img src="/images/plitvice-lakes-1.jpg" alt="plitvice-lakes-1">
            <p>Plitviče Lakes, Croatia</p>
          </div>
        </div>
        <div class="swiper-button-next"></div>
        <div class="swiper-button-prev"></div>
        <div class="swiper-pagination"></div>
      </div>
      
      <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@10/swiper-bundle.min.css" />
      <style>
      .swiper {
        width: 100%;
        max-width: 750px;
        margin: 1rem auto;
        overflow: hidden;
      }
      .swiper-wrapper {
        display: flex;
        flex-wrap: nowrap;
        box-sizing: border-box;
      }
      .swiper-slide {
        min-width: 100% !important;
        display: flex;
        flex-direction: column;
        align-items: center;
        box-sizing: border-box;
        padding: 0;
      }
      .swiper-slide img {
        width: 100% !important;
        max-width: 750px !important;
        height: auto !important;
        display: block;
        margin: 0 auto;
        border-radius: 8px;
      }
      .caption {
        text-align: center;
        font-size: 0.9rem;
        margin-top: 0.5rem;
        padding: 0 0.5rem;
        box-sizing: border-box;
        width: 100%;
      }
      @media (max-width: 600px) {
        .swiper {
          width: 100% !important;
          max-width: 100% !important;
          padding: 0 4%;
          box-sizing: border-box;
        }
        .swiper-slide img {
          width: 100% !important;
          max-width: 100% !important;
          height: auto;
          margin: 0 auto;
          display: block;
        }
        .caption {
          width: 92%;
          font-size: 0.8rem;
          margin: 0.5rem auto 0;
          text-align: center;
          box-sizing: border-box;
        }
        .swiper-button-next,
        .swiper-button-prev {
          display: none;
        }
      }
      body {
        overflow-x: hidden;
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