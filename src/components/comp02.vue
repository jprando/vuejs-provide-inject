<template>
<div>
  C 02
  <comp03 />
  <comp03 />
  <comp03 />
</div>
</template>

<script>

// testando o deep child
// este componente nao faz nada
// alem de fazer referencia ao componente 03
// para ver se a comunicacao entre
// o componente 01 e 03 ira funcionar

  import Comp03 from './comp03'
  export default {
    name: 'comp02',
    components: { Comp03 }
  }
  
</script>
