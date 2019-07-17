<template>
  <section class="main">
    <input-todo></input-todo>
    <todo-list-container></todo-list-container>
  </section>
</template>

<script>
import InputTodo from './InputTodo.vue'
import TodoListContainer from './TodoListContainer.vue'

export default {
  name: 'main-container',
  components: {
    InputTodo,
    TodoListContainer
  }
}
</script>
