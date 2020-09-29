<template>
  <div id="app" class="small-container">
    <h1>Työntekijät</h1>
      <employee-table/>
    <h1>Kaupunkipyörät</h1>
      <kartta/>
      <bikes/>
  </div>
</template>

<script>
  import EmployeeTable from '@/components/Tyontekijataulu.vue'
  import Bikes from '@/components/pyorat.vue'
  import Kartta from '@/components/kartta.vue'

  export default {
    name: 'app',
    components: {
      EmployeeTable,
      Bikes,
      Kartta
    },
  }
</script>

<style>
  h1{
   font-style: italic;
    margin-left: 5px;
  }
</style>