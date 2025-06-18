<template>
    <div>
        <TodoItem />
        <!-- Esta seccion es una combinación de las dos vistas anteriores -->
    </div>
</template>

<script>
import TodoItem from '@/components/TodoItem.vue';

export default {
    name: 'CombinedView',
    components: {
        TodoItem
    }
}
   // Esta sección debe permitir agregar tareas nuevas a la vez que extraer las tareas anteriores de la API
</script>

<style scoped>
/* Aquí pueden agregar estilos personalizados para el componente. */
</style>