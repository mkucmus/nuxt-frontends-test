<script setup lang="ts">
  const { refreshSessionContext, sessionContext } = useSessionContext();
  refreshSessionContext();
</script>
<template>
  <div>
    <pre>{{  sessionContext }}</pre>
    <NuxtWelcome />
  </div>
</template>
