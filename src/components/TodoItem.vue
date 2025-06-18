<template>
    <div>
        <AddTask />
        <TaskList />
    </div>
</template>

<script>
import AddTask from '@/views/AddTask.vue'
import TaskList from '@/views/TaskList.vue';

export default {
    // Define el nombre del componente
    name: 'TodoItem',

    // Define las propiedades que este componente recibirá del componente padre
    // Comentario: Puedes agregar más propiedades si es necesario (por ejemplo, 'dueDate' para la fecha de vencimiento)
    props: {
        title: String,      // Título de la tarea
        completed: Boolean, // Estado de la tarea (completada o pendiente)
    },
    components: {
        AddTask, 
        TaskList
    }
}
</script>

<style scoped>
/* Puedes agregar tus propios estilos aquí */
/* Por ejemplo, cambia el color de fondo de las tareas completadas */

</style>