<template>
  <div>
    <header-bar></header-bar>
    <b-container>
      <b-row class="mt-5">
        <data-table></data-table>
      </b-row>
    </b-container>
  </div>
</template>

<script>
import HeaderBar from "@/components/HeaderBar.vue"; 
import DataTable from "@/components/DataTable.vue";

export default {
  name: 'App',
  components: {
    HeaderBar,
    DataTable
  }
}
</script>

