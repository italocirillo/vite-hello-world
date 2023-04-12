<script>
export default {
    name: "AppHero",
    data() {
        return {
            title: "Jumbotron",
        }
    }

}
</script>


<template>
    <div class="jumbotron">
        <div class="header-jumbotron">
            <h4>{{ title }}</h4>
            <img src="../assets/vue.svg" alt="logo Vue">
        </div>
        <img src="../assets/img/jumbotron.png" alt="Immagine banner">
    </div>
</template>


<style>
.jumbotron {
    width: 80%;
    margin: 0 auto;
    padding: 1em;
    border: 2px solid white;
}

.header-jumbotron {
    text-transform: uppercase;
    display: flex;
    justify-content: space-between;
}
</style>