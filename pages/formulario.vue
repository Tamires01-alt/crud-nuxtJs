<template>
  <div>
    <div>
      <b-table striped hover :items="items"></b-table>
    </div>
    <div>
      <b-button variant="info">Show</b-button>
      <b-button variant="primary">Edit</b-button>
      <b-button variant="danger">Delete</b-button>
    </div>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        items: [
          { id: 1, name: 'no pets', active: 1, order: 2 },
          { id: 2, name: 'no pets', active: 1, order: 2 },
          { id: 3, name: 'no pets', active: 1, order: 2 },
          { id: 4, name: 'no pets', active: 1, order: 2 }
        ]
      }
    }
  }
</script>