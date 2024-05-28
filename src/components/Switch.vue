<script setup lang="ts">
import { SwitchRoot, SwitchThumb } from "radix-vue";
import { ref } from "vue";
import "./Switch.css";

const switchState = ref(false);
</script>

<template>
  <div :style="{ display: 'flex', alignItems: 'center' }">
    <label class="Label" for="airplane-mode"> スイッチ </label>
    <SwitchRoot
      id="airplane-mode"
      v-model:checked="switchState"
      class="SwitchRoot"
    >
      <SwitchThumb class="SwitchThumb" />
    </SwitchRoot>
  </div>
</template>
