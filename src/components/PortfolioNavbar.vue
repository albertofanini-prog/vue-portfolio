<template>
    <nav class="navbar">
        <ul class="router-link_list">
            <router-link class="router-link_item active" to="/">su di me</router-link>
            <router-link class="router-link_item" to="/projects">i miei progetti</router-link>
        </ul>
    </nav>
</template>

<script>
export default {
    name: 'PortfolioNavbar'
}
</script>

<style lang="scss">

.navbar{
    // border: 5px solid purple;
    position: relative;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    height: 75px;
    .router-link_list{
        display: flex;
        align-items: center;
        justify-content: flex-end;
        gap: 30px;
        // border: 3px solid green;
        // width: 80%;
        height: 100%;
    }
}

.router-link_item{
    transition: all 0.4s ease;
    color: #FFF;
    text-transform: uppercase;
    display: block;
    font-weight: 600;
    letter-spacing: 0.2em;
    transition: 0.9s ease-in-out;
    font-size: 1.2rem;
    @media screen and (max-width: 400px){
        width: 50%;
    }
}

.router-link_item:hover{
    opacity: 0.7;
    font-size: 1.6rem;
}
</style>