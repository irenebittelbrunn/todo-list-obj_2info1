<script setup>
defineProps(['id', 'descricao', 'status']);
defineEmits(['editar', 'excluir']);
</script>

<template>
<li>
    {{ descricao }}
    <a href="#" @click.prevent="">Excluir</a>
</li>
</template>
<style scoped>

</style>