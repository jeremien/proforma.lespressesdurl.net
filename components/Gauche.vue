<template>
  <div class="gauche">
    <h1>Œuvre, objet, image, travail</h1>
    <figure>
      <img src="~/assets/image.png" />
      <figcaption>crédits: www.containex.com</figcaption>
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