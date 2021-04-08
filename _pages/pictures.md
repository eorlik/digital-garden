---
layout: page
title: Pictures
id: pictures
permalink: /pictures
---



  <!-- Display picture gallery-->

  <div style="display:block" >
    {% assign pictureList = site.pictures | sort : 'date' | reverse %}
    <div class="containerBox">
      {% for picture in pictureList %}
      <!-- <a class="galleryImage" href="{{picture.url}}"> -->
        <div>
          {% cloudinary pictures/{{picture.image-url}} %}
        </div>
      <!-- </a> -->
      {% endfor %}
    </div>
    </div>

<style>
    a.galleryImage {
        display: block;
        margin: 0 0.4em 0.4em 0;
    }

    .containerBox {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 1rem;
    }

    img {

    }
</style>