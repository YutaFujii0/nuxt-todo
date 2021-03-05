<template>
  <div class="block">
    <add-todo/>
    <filter-todos/>
    <todo-list/>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import TodoList from '~/components/TodoList.vue'
import AddTodo from '~/components/AddTodo.vue'
import FilterTodos from '~/components/FilterTodos.vue'

export default Vue.extend({
  components: { TodoList, AddTodo, FilterTodos },
})
</script>
