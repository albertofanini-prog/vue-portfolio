<template>
    <nav class="navbar">
        <ul class="router-link_list">
            <router-link class="router-link_item active" to="/">home</router-link>
            <router-link class="router-link_item" to="/about">about me</router-link>
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
}

.navbar .line{
    height: 2px;
    position: absolute;
    bottom: 0;
    // margin: 10px 0 0 0;
    background: #FF1847;
}

.router-link_list{
    display: flex;
    align-items: center;
    justify-content: flex-end;
    gap: 30px;
    // border: 3px solid green;
    width: 80%;
    height: 100%;
}

.router-link_item{
    opacity: 0.4;
    transition: all 0.4s ease;
    color: #FFF;
    text-transform: uppercase;
    display: block;
    font-weight: 600;
    letter-spacing: 0.2em;
}

.router-link_item:hover{
    opacity: 0.7;
}

.router-link_item.active{
    opacity: 1;
}

</style>