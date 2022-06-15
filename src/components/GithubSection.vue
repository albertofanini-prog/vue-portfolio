<template>
    <section class="github_section">
        <div class="github_title">
            <h1>GitHub | albertofanini-prog</h1>
            <p>Visita il mio profilo GitHub cliccando <a href="https://github.com/albertofanini-prog">qui</a>.</p>
        </div>
        <div class="card_container">
            <h3>Cards dei progetti.</h3>
            <ul class="card_list">
                <li class="card">
                    <div class="card_img">
                        <img src="../assets/projects_screens/JsArrayCarousel.png" alt="">
                    </div>
                    <div class="card_text">
                        <h4>
                            JS Array Carousel
                        </h4>
                        <p>
                            Carosello di immagini realizzato con HTML, CSS e JS.
                        </p>
                        <p>
                            Visita il codice cliccando <a href="https://github.com/albertofanini-prog/js-array-carousel">qui</a>.
                        </p>
                        <p>
                            Visita il progetto cliccando <a href="https://albertofanini-prog.github.io/js-array-carousel/">qui</a>.
                        </p>
                    </div>
                </li>
                <li class="card">
                    b
                </li>
                <li class="card">
                    b
                </li>
                <li class="card">
                    b
                </li>
            </ul>
        </div>
    </section>
</template>

<script>
export default {
    
}
</script>

<style lang="scss">
.github_section{
    border: 5px solid orange;
    color: #FFF;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

.github_title{
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 10px;
    border: 3px solid green;
    width: 80%;
}

.github_title h1{
    font-size: 1.8rem;
}

.github_title p{
    padding-bottom: 10px;
}

.github_title p a{
    color: #42b983;
    transition: 1s ease-in-out;
}

.github_title p a:hover{
    font-size: 1.6rem;
    transition: 1s ease-in-out;
}

.card_container{
    border: 3px solid green;
    width: 80%;
}

.card_container h3{
    // width: 100%;
    text-align: left;
    padding: 10px 0px;
}

.card_list{
    border: 2px solid yellow;
    width: 100%;
    // height: 600px;
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    gap: 40px;
    padding: 20px 0px;
}

.card{
    border: 1px solid red;
    width: calc((100% / 3) - 40px);
    height: 500px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    border-radius: 15px;
    overflow: hidden;
}

.card_img{
    width: 100%;
    height: 50%;
    overflow: hidden;
}

.card_img img{
    width: 100%;
    height: 100%;
}

.card_text{
    width: 100%;
    height: 50%;
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}
</style>