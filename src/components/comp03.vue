<template>
<div>
  C 03
  {{ rootComp.item.valor }}
  <button @click="rootComp.item.valor++"> teste </button>
</div>
</template>

<script>
  
  export default {
    name: 'comp03',
    inject: ['rootComp']
  }

</script>
