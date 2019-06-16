<template>
  <div class="columns">
    <div class="column">{{ personFullName }}</div>
    <div class="column">{{ companyFullName }}</div>
    <div class="column">{{ streetAddress }}</div>
    <div class="column">{{ cityAndPostalCode }}</div>
  </div>
</template>

<script>
export default {
  name: "Address",
  props: {
    personFullName: String,
    companyFullName: String,
    streetAddress: String,
    cityAndPostalCode: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
