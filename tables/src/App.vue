<template>
  <div id="app">
    <section>
      <b-tabs>
        <b-tab-item label="Buefy Table">
          <BuefyTable/>
        </b-tab-item>
        <b-tab-item label="Bootstrap-vue Table">
          <BootstrapVueTable/>
        </b-tab-item>
      </b-tabs>
    </section>
</div>
</template>

<script>
import BuefyTable from './components/buefyTable.vue';
import BootstrapVueTable from './components/bootstrapVueTable.vue'

export default {
  name: 'App',
  components: {
    BuefyTable,
    BootstrapVueTable
}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
