<template>
  <div class="gauche">
    <h1>Œuvre, objet, image, travail</h1>
    <h2>Pro Forma 1, juin 2021</h2>
    <figure>
      <img src="~/assets/image.png" />
      <figcaption><a href="https://unsplash.com/photos/376KN_ISplE">source de l'image</a></figcaption>
    </figure>
    <br>
    <a href="https://www.dropbox.com/sh/yu2wt2hxiora1hd/AAALtgQtGW4WyAZSv2PUPnx4a?dl=0">Télécharger le pdf</a>
  </div>
</template>

<style>
  .gauche {
    width: 50%;
    background: #f5eee0;
    float: left;
    padding: 20px;
    text-align: center;
    left: 0;
    top: 0;
  }

  .gauche figcaption {
    font-size: 0.8rem;
  }

  .gauche img {
    width: 90%;
    filter: opacity(75%);
    padding: 20px;
  }

  .gauche a {
    color: black;
  }
</style>