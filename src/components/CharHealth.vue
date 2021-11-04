<template>
  <div class="charsheet-stats__health-row">
    <div class="charsheet-stats__data-block">
      <span class="charsheet-stats__data-info charsheet-stats__data-info--type">Ponits de Santé de Départ</span>
      <span class="charsheet-stats__data-info" v-text="starting_hits"></span>
    </div>

    <div class="charsheet-stats__data-block">
      <span class="charsheet-stats__data-info charsheet-stats__data-info--type">Blessure Grave</span>
      <span class="charsheet-stats__data-info" v-text="seriously_wounded"></span>
    </div>

    <div class="charsheet-stats__data-block">
      <span class="charsheet-stats__data-info charsheet-stats__data-info--type">Sauvegarde Contre la Mort</span>
      <span class="charsheet-stats__data-info" v-text="death_save"></span>
    </div>
  </div>
</template>

<script>
  export default {
    name: "CharHealth",
    props: ['starting_hits', 'seriously_wounded', 'death_save'],
  }
</script>
