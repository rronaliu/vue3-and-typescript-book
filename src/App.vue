<template>
  <div id="app">
    <ItemsList />
  </div>
</template>

<script lang="ts">
import ItemsList from './components/ItemsList.vue'

export default defineComponent({
  name: 'App',
  components: {
    ItemsList
  }
})
</script>
