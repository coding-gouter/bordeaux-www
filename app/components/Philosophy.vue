<template>
  <section class="philosophy">
    <h2>{{ msg }}</h2>
	<p>Passionnés d'informatique et de pédagogie ludique, acteurs locaux de la scène web et militants, nous savons que l'informatique se découvre dès 6 ans ! Via <i>un language adapté</i>, les enfants se familiarisent dès le premier coding gouter avec des <i>notions élémentaires</i> mais centrales de la programmation. L'assignation d' "actions" ("fonctions" pour les adultes), d'évènements, de répétitions (boucles!) et de conditions peuvent être abordées par le jeu. Le jeune enfant peut ordonancer puis lancer des actions selon son imagination, tester, apprendre par essais / erreur ou par l'échange avec ses camarades ou professeurs pour enfin constater avec enthousiaste la réalisation par l'ordinateur de son projet !</p>
  </section>
</template>

<script>
  export default {
    data () {
      return {
        msg: 'Philosophie'
      }
    }
  }
</script>
