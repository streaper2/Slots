<template>
    <div>
        <img src="https://upload.wikimedia.org/wikipedia/commons/b/bb/Andrew_Marvell_portrait.jpg" alt="andrew marvell">
        <h1 slot="title"> The Garden</h1>
        <p slot="poem"> How vainly men themselves amaze
            To win the palm, the oak, or bays,
            And their uncessant labours see
            Crown’d from some single herb or tree,
            Whose short and narrow verged shade
            Does prudently their toils upbraid;
            While all flow’rs and all trees do close
            To weave the garlands of repose.</p>
        <h3 slot="author"> Andrew Marvell </h3>
    </div>
</template>

<script>

</script>

<style scoped>
    div {
        border: 1px solid green;
        background-color: lightgreen;
        padding: 30px;
        margin: 20px auto;
        text-align: center
    }
</style>