<template>
  <div class="box hax-text-weight-bold" :style="estilos">
    <slot></slot>
  </div>
</template>

<script lang="ts">

import { defineComponent } from 'vue';

export default defineComponent ({
    name: 'BoxPadrao',
    data () {
      return {
        estilos: {
          backgroundColor: '#FAF0CA'
        }
      }
    }
})

</script>
