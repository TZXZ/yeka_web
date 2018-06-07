<!-- Home Page -->
<template>
    <div id="container" onClick={}>
        <button v-on:click="count += 1">Add 1</button>
        <p>The button above has been clicked {{ count }} times.</p>
        <h2>Some Thing is Happen</h2>
    </div>
</template>


<script>
    export default {
        name: 'Home',
        data: {
            count: 0,
        },
    }
</script>


<style>
    #container {
        width: 80%;
        height: 20%;
        margin-top: 2%;
        background-color: rgb(132, 235, 163);
    }
</style>