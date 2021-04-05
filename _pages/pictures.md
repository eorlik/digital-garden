---
layout: default
title: Pictures
id: pictures
permalink: /pictures
---



  <!-- Display picture gallery-->

  <div style="display:block" >
    {% assign pictureList = site.pictures | sort : 'date' | reverse %}
    <container class="containerBox">
      {% for picture in pictureList %}
      <a class="galleryImage" href="{{picture.url}}">
        <div>
          <img src="/pictures/{{picture.image-url}}"  />
        </div>
      </a>
      {% endfor %}
    </container>
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
    }

    .artwork {
        max-height: 500px;
        margin: 0 20px

    }
</style>