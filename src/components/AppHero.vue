<script>
export default {
    
}
</script>

<template lang="">
    <div>
        <div class="jumbotron">
            <h2>Questo è solo l'inizio</h2>
        </div>
    </div>
</template>

<style scoped>
    .jumbotron{
        height: 400px;
        width: 100%;
        background-image: url('https://picsum.photos/1600/400');
        background-position: center;
        position: relative;
    }
    .jumbotron h2{
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        text-transform: uppercase;
        color: white;
    }
</style>