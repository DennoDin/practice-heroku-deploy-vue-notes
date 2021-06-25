<template>
    <div>
        <entry-form v-on:addTask="addTask"/>
        <task-list :taskList="tasks"/>
    </div>
</template>

<script>
import EntryForm from './EntryForm.vue'
import TaskList from './TaskList.vue'

export default ({
    name: 'Main',
    components:{
        EntryForm,
        TaskList,
    },
    data: () => ({
        tasks: [],
    }),
    methods: {
        addTask(item){
            this.tasks.push(item);
        }
    }
})
</script>
