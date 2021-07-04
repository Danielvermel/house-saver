<template>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <NuxtLink class="navbar-brand" to="/">House Saver</NuxtLink>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">
                <li class="nav-item" id="home">
                    <NuxtLink class="nav-link"  to="/">Home <span class="sr-only">(current)</span></NuxtLink>
                </li>
                <li class="nav-item" id="products">
                    <NuxtLink class="nav-link" to="/products">Products</NuxtLink>
                </li>
            </ul>
            <ul class="navbar-nav ml-auto">
                <li class="nav-item" id="myItems">
                    <NuxtLink class="nav-link" to="/my-items">My Items</NuxtLink>
                </li>
            </ul>
        </div>
    </nav>
</template>

<script>
    export default {
    }
</script>

<style scoped>
    .card-container {
        width: 24%;
        height: 12.5rem;
        border-radius: 0.5rem;
        overflow: hidden;
        margin-bottom: 1.5rem;
        cursor: pointer;
    }
    .image {
        width: 100%;
        height: 100%
    }
</style>