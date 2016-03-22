<template>
  <section class="action">
    <h2>{{ msg1 }}</h2>
<ul>
	<li><strong>Mise en place</strong> -- organisation de l'espace mis à disposition pour accueillir les enfants et parents</li>
	<li><strong>Accueil</strong> -- nous accueillons les participants, distribuons des badges avec les noms</li>
	<li><strong>Présentation</strong> -- Et alors ? L'équipe c'est qui ? Le programme c'est quoi ? Coder ça fait quoi ? On a la réponse !</li>
	<li><strong>Phase 1: On démarre !</strong> -- vos machines sont prêtes ? Un parcours guidé vous familiarise avec les principes de base</li>
	<li><strong>Pause gouter</strong> -- les champions, ça casse la croutte et ça tourne au jus de pommes !</li>
	<li><strong>Phase 2: action libre !</strong> -- alors... qu'est qu'on peut créer maintenant ?...</li>
</ul></p>
  </section>
  <section class="action">
    <h2>{{ msg2 }}</h2>
	<p><ul>
	<li>Atelier Code.org (6-14 ans) -- atelier de découverte avec Angry Bird, l'Age de glace et MineCraft !</li>
	<li>Atelier Scratch (8-14 ans) -- programmation créative sur la plateforme du MIT !</li>
	<li>Atelier Pygame (12-18 ans) -- le Labyrinthe Donkey Kong avec notre stagaire de 3e, en 1e semaine</li>
	<li>Atelier d'Initiation au Web (14-18 ans) -- découverte de la programmation web HTML/CSS/JS en ligne avec JSfiddle, Codio, et autres !</li>
	</ul></p>
<img class="" src="../assets/coding.png" />
<img class="" src="../assets/codio_IDE.png" />
  </section>

</template>

<script>
  export default {
    data () {
      return {
        msg1: 'Action / Prestation / Déroulement',
        msg2: "Types d'ateliers"
      }
    }
  }
</script>

