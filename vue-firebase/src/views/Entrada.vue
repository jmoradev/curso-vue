<template>
  <div class="entrada">
    <span>Entrada</span>
    <cliente />
  </div>
</template>

<script>
import Cliente from '@/components/Cliente.vue'
export default {
  components: {
    Cliente
  }
}
</script>

<style >
.entrada {
  margin: 10px;
  padding: 10px;
  background-color: #553f75;
  font-size: 2.4rem;
}
</style>