<template>
  <h1>lifecicle hooks</h1>
</template>

<script>
// export default {
//   mounted() {
//     console.log("Foi montado Options API!");
//   },
// };
import { onMounted } from '@vue/runtime-core'
export default {
  setup(){
    onMounted(() => {
      console.log("Foi montado Composition API!");
    })
  }
}
</script>
