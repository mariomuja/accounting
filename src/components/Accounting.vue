<template>
  <div>
    <h1>{{ msg }}</h1>
    <p>test</p>

    <div class="columns">
      <div class="column">
        <Address personFullName="Mario Muja"></Address>
      </div>
      <div class="column">
        <Address personFullName="Mario Muja"></Address>
      </div>
      <div class="column">Auto</div>
    </div>
  </div>
</template>

<script>
import Address from "./Address";

export default {
  name: "accounting",
  components: {
    Address
  },
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
