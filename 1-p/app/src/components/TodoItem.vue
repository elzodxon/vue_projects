<template>
  <div class="todo-item" v-bind:class="{'is-complete':todo.completed}">
    <div class="todo-first" style="display: flex; align-items: center;">
      <input type="checkbox" v-on:change="markComplete">
      <p>{{todo.title}}</p>
    </div>
    <button @click="$emit('del-todo', todo.id)" class="del">X</button>
  </div>
</template>

<script>
export default {
  name: "TodoItem",
  props: ['todo'],
  methods: {
    markComplete(){
      this.todo.completed = !this.todo.completed
    }
  }
}
</script>

<style scoped>
  .todo-item{
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #f4f4f4;
    padding: 10px;
    border-bottom: 1px #ccc dotted;
  }

  .is-complete{
    text-decoration: line-through;
  }
  .del{
    background: #ff0000;
    color: white;
    border-radius: 50%;
    border: none;
    height: 30px;
    width: 30px;
  }

  input[type='checkbox']{
    margin-right: 20px;
  }
</style>