<template>
<div>
  C 01 {{ item.valor }}
  <comp02 />
</div>
</template>

<script>

import Comp02 from './comp02'

export default {
  name: 'comp01',
  components: { Comp02 },
  data() {
    return {
      item: { valor: 0 }
    }
  },
  provide() {
    return {
      rootComp: this
    }
  }
}

</script>
