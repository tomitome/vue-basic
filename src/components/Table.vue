<template>
  <div>
    <b-table striped hover :items="items" :fields="fields"></b-table>
  </div>
</template>

<script>
export default {
  data(){
    return{
      fields:[
        {key:'name', sortable: false, varient:'danger'},
        {key:'price', sortable: true},
        {key: 'count', sortable: true},
      ],
      items:[
        {"name":"apple", "price":120, "count":7},
        {"name":"orange", "price":300, "count":112},
      ]
    }
  }
}
</script>