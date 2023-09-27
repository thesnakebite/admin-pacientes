<script setup>
    import { computed } from 'vue'

    const props = defineProps({
        alerta: {
            type: Object,
            required: true
        }
    })

    const isError = computed( () => {
        return props.alerta.tipo === 'error'
    })
</script>

<template>
    <div :class="isError ? 'bg-red-200 text-red-600' : 'bg-green-200 text-green-600'" 
         class="font-bold text-center rounded-md p-4 mb-3"
    >
        {{ alerta.mensaje }}
    </div>
</template>

<style lang="sass" scoped>

</style>