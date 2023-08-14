<script setup lang="ts"></script>

<template>
  <div>
    <q-btn-toggle
      toggle-color="primary"
      push
      spread
      :options="[
        { label: 'All', value: 'all' },
        { label: 'Open', value: 'open' },
        { label: 'Closed', value: 'closed' },
      ]"
    ></q-btn-toggle>
  </div>
</template>
