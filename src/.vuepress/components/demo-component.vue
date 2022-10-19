<template>
  <p class="demo">
    {{ msg }}
  </p>
</template>

<script>
import { ref } from 'vue'

export default {
  setup() {
    const msg = ref('hadjka')

    return {
      msg,
    }
  },
}
</script>
