<template>
    <button @click="incrementar">Incrementar</button>
    <p>{{ count }}</p>
    <button @click="decrementar">Decrementar</button>
</template>

<script setup>

  const count = ref(0);

  function incrementar(){
    count.value++;
  }
  function decrementar(){
    count.value--;
  }
</script>