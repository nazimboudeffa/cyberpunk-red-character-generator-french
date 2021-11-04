<template>
  <section class="charsheet-style" >
    <div class="charsheet-style__block">
      <h3 class="charsheet-style__title">Habits</h3>
      <p class="charsheet-style__content">
        {{ !emptyStyle ? appearance.clothes : '' }}
      </p>
    </div>

    <div class="charsheet-style__block">
      <h3 class="charsheet-style__title">Cheuveux</h3>
      <p class="charsheet-style__content">
        {{ !emptyStyle ? appearance.hair : '' }}
      </p>
    </div>

    <div class="charsheet-style__block">
      <h3 class="charsheet-style__title">Affectations</h3>
      <p class="charsheet-style__content">
        {{ !emptyStyle ? appearance.affectations : '' }}
      </p>
    </div>

    <div class="charsheet-style__block">
      <h3 class="charsheet-style__title">Origine et Langue</h3>
      <p class="charsheet-style__content">
        {{ !emptyStyle ? appearance.origin : '' }}
      </p>
    </div>
  </section>
</template>

<script>
  export default {
    name: "CharStyle",
    props: ['appearance', 'emptyStyle'],
  }
</script>
