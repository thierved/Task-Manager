<template>
    <header>
        <h1>Task Manager</h1>
        <button class="new-task">New Task</button>
    </header>
</template>

<script>

</script>

<style scoped>


header {
    padding: 1rem;
    border-bottom: 2px solid rgba(255, 255, 255, 0.3);
}

.new-task {
    width: 20%;
    margin: 1rem auto;
}

@media (max-width: 651px) {
    .new-task {
        width: 80%;
    }
}
</style>