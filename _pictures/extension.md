---
title: Architectural sketches
image-url: assets/extension1.jpg
layout: default
date: '2021-04-03'
---

<div class="containerBox">

<img class="artwork" title="{{page.title}}" src= "/pictures/{{page.image-url}}" />


<img class="artwork" title="{{page.title}}" src= "/pictures/assets/extension2.jpg" />
</div>

<style>
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
