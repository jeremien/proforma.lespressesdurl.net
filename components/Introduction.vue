<template>
  <div class="droite intro"
    @click="close"
  >
    <p>(Extrait)</p><br>
    <h1>Publication assistée par ordinateur</h1>
    <p>Les presses d’URL s’attellent à rassembler des propositions d’édition qui agencent des chaînes de publication singulières, organisées autour de programmes informatiques qui sont partie prenante du geste artistique, à la fois outils et coéquipiers, développés spécifiquement pour la conception et la production de l’ouvrage.</p>
    <br>
    <h1>Écrire sa chaîne de publication programmatique</h1>
<p>Sans entrer dans les détails techniques de la programmation de cette première publication, nous pouvons résumer en quelques points les principes moteurs derrière l’ouvrage. En premier lieu, l’interopérabilité des formats de données – avec l’utilisation du markdown, yaml, et html pour le texte et les métadonnées – garantit une circulation fluide des contenus et une traduction fidèle pour la mise en forme du livre. […] L’action suivante est le traitement automatique de la langue : les textes sont interprétés selon leur syntaxe, et décortiqués pour être réduits à des fragments computationables, c’est-à-dire qu’un nom ou un verbe est associé à une valeur unique, identifiable par le langage de programmation, on parle alors d’étiquetage morpho‑syntaxique. […]</p>
<p>Nous avons choisi d’intituler la collection Pro Forma en référence au coup d’essai qui donne un aperçu du document définitif mais reste modifiable si les parties ne s’accordent pas. Conçue comme un ensemble de publications numérotées et datées, la collection Pro Forma offre la possibilité de recueillir un certain nombre de textes sans limite quantitative ou thématique. Le titre du premier numéro marque l’intérêt du dispositif puisque la juxtaposition des mots « Œuvre, objet, image, travail » s’est faite selon une sélection automatisée des rares termes présents dans au moins huit des dix textes.</p>
<br>
<h1>Un outil pour déspécialiser les savoirs</h1> 
<p>Dans le contexte de cette première publication, notre principal intérêt à l’usage de cette chaîne de publication programmatique était de pouvoir réunir différents textes sans lien évident et pourtant, d’apprécier des interrelations lexicologiques, temporelles et référentielles saisies grâce à l’informatique. L’hétérogénéité des sujets traités et des méthodologies employées par les auteurs a donc marqué notre manière d’appréhender l’édition de cet ouvrage. […] En plus de recueillir un ensemble de ressources, l’édition du document permet de croiser les points de vue en faveur d’une déspécialisation des savoirs et de l’idée que, puisque toute pensée évolue avec son temps et ses mises enrelation, la manière dont on y accède est un enjeu de société. Pour cette première édition, l’ouvrage se compose de dix textes rédigés par des enseignants‑chercheurs, des chercheurs et des artistes‑chercheurs du domaine des arts.</p>
</div>
</template>

<script>
export default {
  name: 'Introduction',
  methods: {
    close() {
      this.$emit('close')
    }
  }
}
</script>

<style>
  .intro {
    background-color: #f5eee0;
    cursor: pointer;
  }
</style>