<script setup>
import { ref, onMounted } from 'vue'

const event = ref(null)

onMounted(() => {
  // fetch event (by id) and set local event data
  // busca o evento (por id) e define os dados do evento local
  
})
</script>

<template>
  <div>
    <h1>{{ event.title }}</h1>
    <p>{{ event.time }} on {{ event.date }} @ {{ event.location }}</p>
    <p>{{ event.description }}</p>
  </div>
</template>