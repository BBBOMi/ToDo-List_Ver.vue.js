<template>
  <div id="todolistapp">
    <section class="todoapp">
      <todo-header></todo-header>
      <section class="main">
        <input class="toggle-all" type="checkbox">
        <ul class="todo-list">
          <li class="todo">
            <div class="view">
              <input type="checkbox" class="toggle"/>
              <button class="destroy"></button>
            </div>
            <input type="text" class="edit">
          </li>
        </ul>
      </section>
      <footer class="footer">
        <span class="todo-count">
          <strong></strong>0 left
        </span>
        <ul class="filters">
          <li><a href="#/all>">All</a></li>
          <li><a href="#/active">Active</a></li>
          <li><a href="#/completed">Completed</a></li>
        </ul>
        <button class="clear-completed">
          Clear completed
        </button>
      </footer>
    </section>
    <footer class="info">
      <p>Double-Click to edit a todo</p>
      <p>Written by Bomi</p>
      <p>Part of <a href="http://todomvc.com">TodoMVC</a></p>
    </footer>
    <!--<img src="./assets/logo.png">-->
    <!--<router-view/>-->
  </div>
</template>

<script>
  import TodoHeader from "./components/header/Header.vue";

export default {
  name: 'todo-list',
  components: {
    TodoHeader
  },
}
</script>

<style>
</style>
