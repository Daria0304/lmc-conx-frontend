<template>
  <div class="fleet-manager">
    <div class="list">
      here goes list of machines
    </div>
    <div class="details">
      here goes the details of a selected machine
    </div>    
  </div>
</template>

<script>

export default {
  name: 'FleetManager',
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.list, .details {
  display: inline-block;
  margin: 20px;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}
</style>
