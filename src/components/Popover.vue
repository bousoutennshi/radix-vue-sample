<script setup lang="ts">
import { PopoverContent, PopoverPortal, PopoverRoot, PopoverTrigger } from 'radix-vue'
</script>

<template>
  <PopoverRoot>
    <PopoverTrigger>ここを押すと</PopoverTrigger>
    <PopoverPortal>
      <PopoverContent>
        さらなるコンテンツが表示されます
      </PopoverContent>
    </PopoverPortal>
  </PopoverRoot>
</template>
