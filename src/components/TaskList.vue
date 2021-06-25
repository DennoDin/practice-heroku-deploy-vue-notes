<template>
    <div>
        <h2>Tasks</h2>
        <div v-for="(details, id) of taskList" :key=id>
            <task-item :details="details" :index="id"/>
        </div>
    </div>
</template>

<script>
import TaskItem from './TaskItem.vue'

export default ({
    components:{
        TaskItem,
    },
    props:{
        taskList: Object,
    }
})
</script>
