<template>
  <div class="fullscreen    text-center q-pa-md flex flex-center" style="opacity: 0.7;color: rgb(78, 131, 253);">
    <div>
      <div style="font-size: 25vh">
        404
      </div>

      <div class="text-h2" style="opacity:.4">
        Oops. It seems you are in a wrong page
      </div>

      <q-btn class="q-mt-xl tw-animate-bounce" icon="rocket" color="white" text-color="blue" unelevated to="/"
        label="take you home" no-caps />
    </div>
  </div>
</template>

<script>
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'ErrorNotFound'
})
</script>
