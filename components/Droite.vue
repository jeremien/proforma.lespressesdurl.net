<template>
  <div class="droite">
    <p>Cet ouvrage collectif résulte d’une collaboration entre les presses d’URL, 
      le Laboratoire ECLLA de l’Université Jean Monnet Saint‑Étienne et le Random(lab) de l’École supérieure d’art et design de Saint‑Étienne.</p> 
      
    <br>
    <h1>Direction scientifique</h1>
    <p>Gwenaëlle Bertrand, enseignante‑chercheuse 
      et designer et Jérémie Nuel, enseignant et designer graphique, 
      responsable des presses d’URL.</p>
    <br>
    <h1>Conception de la maquette <br>et éditorialisation des contenus</h1>
    <p>Maxime Bouton et Émile Greis, designers graphiques et développeurs.</p> 
    <br>
    <h1>Auteurs</h1>
    <p>Sandra et Gaspard Bébié‐Valérian, Gwenaëlle Bertrand, Léonore Bonaccini, Céline Cadaureille, Anne‐Céline Callens, Maxime Favard, Xavier Fourt, Thibault Honoré, Nolwenn Maudet, Rodolphe Olcèse, Jacopo Rasmi, Sophie Suma.</p>
    <br>
    <h1>Les presses d'URL</h1>
    <p>Les presses d’URL s’attèlent à rassembler des propositions d’édition qui agencent des chaînes de publication singulières, organisées autour de
      programmes informatiques qui sont partie prenante du geste artistique, à la fois
      outils et coéquipiers, développés spéciﬁquement pour la conception et la
      production de l’ouvrage.</p>
    <br>
    <h1>Sommaire</h1>
    <ul>
      <li><p class="link" @click="openIntro">Introduction</p>
          <p>Gwenaëlle Bertrand et Jérémie Nuel</p></li>
    
      <li><p>Au plus près des morts</p>
          <p>Céline Cadaureille</p></li>
      <li><p>Mycore, fragments pour un devenir humain</p>
          <p>Sandra et Gaspard Bébié‑Valérian</p></li>
      <li><p>Le monolithe ou la nuit cinématographique : fortune de la sculpture dans 2001: l’odyssée de l’espace</p>
          <p>Thibault Honoré</p></li>
      <li><p>Le motif de la technique</p><p>Rodolphe Olcèse</p></li>
      <li><p>William Miller et son « Good Design » radicalement inventif</p><p>Maxime Favard</p></li>
      <li><p>Les Éditions Paul‑Martial ou l’art de la mise en page</p><p>Anne‑Céline Callens</p></li>
      <li><p>Cartographier et représenter les complexités : entretien avec Léonore Bonaccini et Xavier Fourt</p><p>Gwenaëlle Bertrand</p></li>
      <li><p>Le design comme angle mort des algorithmes de curation</p><p>Nolwenn Maudet</p></li>
      <li><p>Notes sur nos sous‑politiques culturelles</p><p>Jacopo Rasmi</p></li>
      <li><p>Les dramalités spatiales et architecturales de Trump</p><p>Sophie Suma</p></li>
    </ul>
  </div>
</template>

<script>
export default {
  methods: {
    openIntro() {
      this.$emit('open')
    }
  }
}
</script>

<style>
  .droite {
    width: 50%;
    background: white;
    overflow: scroll;
    padding: 20px;
    /* margin-right: 50px; */
  }

  .droite li {
    list-style: none;
    margin-top: 20px;
  }

  .link {
    text-decoration: underline;
    cursor: pointer;
  }
</style>