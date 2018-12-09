<template>
  <div>
    <todo-list v-bind:todos="todos"></todo-list>
  </div>
</template>

<script>
import TodoList from './components/TodoList'

export default {
  name: 'App',
  components: {
    TodoList
  }
}
</script>

<style>
</style>
