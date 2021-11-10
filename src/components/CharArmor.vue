<template>
  <section class="charsheet-armor">
    <h3 class="charsheet-armor__title">Armure</h3>
    <table class="charsheet-armor__table">
      <tbody>
        <tr>
          <th>Tête</th>
          <td v-text="armor.head.name"></td>
          <td v-text="armor.head.sp" class="charsheet-weapons__info-number"></td>
        </tr>
        <tr>
          <th>Corps</th>
          <td v-text="armor.body.name"></td>
          <td v-text="armor.body.sp" class="charsheet-weapons__info-number"></td>
        </tr>
      </tbody>
    </table>
  </section>
</template>

<script>
  export default {
    name: "CharArmor",
    props: ['armor'],
  }
</script>
