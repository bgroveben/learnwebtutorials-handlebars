<template>
  <div>
    // Javascript expressions in Vue are enclosed in double curly brackets
    <p>Completed Tasks: {{todos.filter(todo => {return todo.done == true}).length}}</p>
    <p>Pending Tasks: {{todos.filter(todo => {return todo.done == false}).length}}</p>
  </div>
</template>
