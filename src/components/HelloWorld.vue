<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>
</div>
<div>
  <h1>BIODATA PRIBADI</h1>
  <h2>nama : muhammad irfan saputra</h2>
  <h2>npm : 233510261</h2>
  <h2>fakultas : teknik</h2>
  <h2>prodi : teknik informatika</h2>
  <h2>email : m.irfansaputra0089@gmail.com</h2>
 
</div>

</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
