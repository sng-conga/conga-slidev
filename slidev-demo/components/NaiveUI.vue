<template>
   <n-calendar @update:value="handleUpdateValue" #="{ year, month, date }">
    {{ year }}-{{ month }}-{{ date }}
  </n-calendar>
</template>

<script setup>
import { NCalendar} from 'naive-ui'
</script>