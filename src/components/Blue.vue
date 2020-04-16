<template>
    <div>
        <img src="https://upload.wikimedia.org/wikipedia/commons/3/36/Robert_Frost%2C_1910s.jpg" alt="robert frost">
        <h1 slot="title"> Fragmentary Blue</h1>
        <p slot="poem"> Why make so much of fragmentary blue
            In here and there a bird, or butterfly,
            Or flower, or wearing-stone, or open eye,
            When heaven presents in sheets the solid hue?

            Since earth is earth, perhaps, not heaven (as yet)—
            Though some savants make earth include the sky;
            And blue so far above us comes so high,
            It only gives our wish for blue a whet.</p>
        <h3 slot="author"> Robert Frost </h3>
    </div>
</template>

<script>

</script>

<style scoped>
    div {
        border: 1px solid blue;
        background-color: lightblue;
        padding: 30px;
        margin: 20px auto;
        text-align: center
    }
</style>