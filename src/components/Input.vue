<script setup lang="ts" generic="P extends Inputs">
import type { Inputs } from '../props.ts'

const props = defineProps<P>()
</script>

<template>
  {{ props }}
</template>