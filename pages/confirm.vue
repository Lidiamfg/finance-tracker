<template>
    <UCard>
        <template #header> Signing in... </template>

        Wait a momement while we sign you in...
    </UCard>
</template>

<script setup>
useRedirectIfAuthenticated();
</script>
