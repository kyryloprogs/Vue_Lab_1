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

    <p>
      Name: Kyrylo Mytroshyn

    </p>
    <p>
      Specialistation: 121
    </p>
    <p>
      Group: 8.1212 -1-іпз
    </p>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
