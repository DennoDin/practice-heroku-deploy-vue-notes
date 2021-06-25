<template>
    <div>
        ID: {{index}} - {{details}}
    </div>
</template>

<script>

export default ({
    data: () => ({}),
    props: {
        details: String,
        index: Number,
    }
})
</script>
