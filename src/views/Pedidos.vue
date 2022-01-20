<template>
  <div>
    <div class="main-container">
      <h1>Administrar Pedidos:</h1>
      <Dashboard />
    </div>
  </div>
</template>

<script>
import Dashboard from '../components/Dashboard'
export default {
  name: 'Pedidos',
  components: {
    Dashboard
  }
}
</script>