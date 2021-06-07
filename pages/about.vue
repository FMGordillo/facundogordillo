<template>
  <div>
    <p>Estas ahora en {{ route }}</p>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  data: () => ({
    route: 'AKSDOKASODKASOD',
  }),
})
</script>
