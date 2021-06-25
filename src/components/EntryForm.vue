<template>
    <div>
        <h2 class="newTask">New Task</h2>
        <input v-model="task" placeholder="Enter Task">
        <button v-on:click="$emit('addTask', task)">Submit</button>
    </div>
</template>

<script>

export default ({
    data: () => ({
        task: ""
    }),
    methods: {
    }
})
</script>

<style scoped>
.newTask{
    padding: 2px;
    margin: 1px;
}
</style>