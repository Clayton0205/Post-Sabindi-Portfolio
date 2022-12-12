<template>
    <div id="page">
        <div class="container-fluid">
            <div class="row" id="titleName">
                <h2>Clayton Adonis</h2>
                <h1>Aspriring Developer</h1>
                <h1 class="animate__animated animate__bounce">An animated element</h1>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
* {
    margin: 0;
    padding: 0;
}

#page {
    background-image: radial-gradient(circle, #6d493b, #c19b87);
    width: 100vw;
    height: 100vh;
    text-align: center;
}

#titleName {
    width: 50vw;
    margin: auto;
    padding-top: 45vh;
    color: #f1e9e3;
    border-bottom: inset #f1e9e3 5px;
}
</style>