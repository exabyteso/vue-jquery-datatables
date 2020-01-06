<template>
  <div id="app">
      <div class="row" style="padding: 5%;">
        <div class="col-12">
          <Datatable msg="Welcome to Your Vue.js App"/>
        </div>
      </div>
  </div>
</template>

<script>
import Datatable from './components/Datatable.vue'

export default {
  name: 'app',
  components: {
    Datatable
  }
}
</script>
