<template>
    <section class="github_section">
        <div class="github_title">
            <h1>GitHub | albertofanini-prog</h1>
            <p>Visita il mio profilo GitHub cliccando <a target="_blank" href="https://github.com/albertofanini-prog">qui</a>.</p>
        </div>
        <div class="card_container">
            <h3>Alcuni dei progetti per me più significativi realizzati durante il master in Boolean.</h3>
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
                            Visita il codice cliccando <a target="_blank" href="https://github.com/albertofanini-prog/js-array-carousel">qui</a>.
                        </p>
                        <p>
                            Visita il progetto cliccando <a target="_blank" href="https://albertofanini-prog.github.io/js-array-carousel/">qui</a>.
                        </p>
                        <p class="data_p">
                            10/02/2022
                        </p>
                    </div>
                </li>
                <li class="card">
                    <div class="card_img">
                        <img src="../assets/projects_screens/VueToDoList.png" alt="">
                    </div>
                    <div class="card_text">
                        <h4>
                            Vue ToDoList
                        </h4>
                        <p>
                            ToDoList realizzata con VueJS.
                        </p>
                        <p>
                            Visita il codice cliccando <a target="_blank" href="https://github.com/albertofanini-prog/vue-todolist">qui</a>.
                        </p>
                        <p>
                            Visita il progetto cliccando <a target="_blank" href="https://albertofanini-prog.github.io/vue-todolist/">qui</a>.
                        </p>
                        <div class="data_p">
                            26/02/2022
                        </div>
                    </div>
                </li>
                <li class="card">
                    <div class="card_img">
                        <img src="../assets/projects_screens/Boolzapp.png" alt="">
                    </div>
                    <div class="card_text">
                        <h4>
                            Boolzapp
                        </h4>
                        <p>
                            Replica di Whatsapp con searchbar per il filtraggio dei contatti e risposta automatica. Realizzata con HTML, CSS, JS.
                        </p>
                        <p>
                            Visita il codice cliccando <a target="_blank" href="https://github.com/albertofanini-prog/js-html-css-boolzap">qui</a>.
                        </p>
                        <p>
                            Visita il progetto cliccando <a target="_blank" href="https://albertofanini-prog.github.io/js-html-css-boolzap/">qui</a>.
                        </p>
                        <div class="data_p">
                            28/02/2022
                        </div>
                    </div>
                </li>
                <li class="card">
                    <div class="card_img">
                        <img src="../assets/projects_screens/VueNetflix.png" alt="">
                    </div>
                    <div class="card_text">
                        <h4>
                            Netflix
                        </h4>
                        <p>
                            Replica di Netflix realizzata con VueJS che, recuperando i dati da TheMovieDatabase, mostra i risultati in pagina.
                            Tramite la searchbar è possibile ricercare i film o le serie tv scrivendo il titolo.
                            Quando il cursore viene spostato sopra al film, verranno mostrati: il titolo originale, il titolo tradotto, la lingua originale
                            trasformata da sigla (EN, IT...) a bandiera. La descrizione e il voto numerico trasformato da numero a stella.
                        </p>
                        <p>
                            Visita il codice cliccando <a target="_blank" href="https://github.com/albertofanini-prog/vue-netflix">qui</a>.
                        </p>
                        <div class="data_p">
                            15/03/2022
                        </div>
                    </div>
                </li>
                <li class="card" id="laravel_card">
                    <div class="card_img">
                        <img src="../assets/projects_screens/laravel_backoffice_index.png" alt="">
                    </div>
                    <div class="card_text">
                        <h4>
                            Laravel backoffice
                        </h4>
                        <p>
                            Backoffice realizzato con Laravel.
                            Il login è protetto da autenticazione,
                            la registrazione richiede di confermare l'e-mail di verifica attraverso MailTrap.
                            Tutti i form sono forniti di validazione sia server-side sia client-side.
                            Completo di tutte le curd: create, show, soft-delete, edit.
                            L'applicativo è collegato al database MySQL e popolato da faker. 
                        </p>
                        <p>
                            Visita il codice cliccando <a target="_blank" href="https://github.com/albertofanini-prog/laravel-vue-router">qui</a>.
                        </p>
                        <div class="data_p">
                            02/04/2022
                        </div>
                    </div>
                </li>
            </ul>
        </div>
    </section>
</template>

<script>

export default {
    components: {
    }
}
</script>

<style lang="scss">
.github_section{
    // border: 5px solid orange;
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
    // border: 3px solid green;
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
    // border: 3px solid green;
    width: 90%;
}

.card_container h3{
    // width: 100%;
    text-align: center;
    padding: 10px 0px;
}

.card_list{
    // border: 2px solid yellow;
    width: 100%;
    // height: 600px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
    gap: 40px;
    padding: 20px 0px;
}

.card{
    // border: 1px solid red;
    width: calc((100% / 2) - 40px);
    // min-height: 550px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    border-radius: 15px;
    overflow: hidden;
    box-shadow: rgba(255, 255, 255, 0.15) 0px 5px 15px;
    opacity: 0.6;
    transition: 0.5s ease-in-out;
}

@media screen and (max-width: 880px){
    .card{
        width: calc(90% - 40px);
    }
}

.card:hover{
    opacity: 1;
}

.card_img{
    width: 100%;
    height: 60%;
    overflow: hidden;
}

.card_img img{
    width: 100%;
    height: 100%;
}

.card_text{
    width: 100%;
    height: 40%;
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-start;
    gap: 10px;
    position: relative;
    padding: 20px 5px;
}

.card_text h4{
    font-size: 1.6rem;
    transition: 0.3s ease-in-out;
}
.card_text p{
    // max-width: 90%;
    padding: 0 5px;
}

.card_text h4:hover{
    color: #42b983;
}

.data_p{
    position: absolute;
    left: 2%;
    bottom: 3%;
    font-size: 0.7rem;
}

.laravel{
    width: calc(90% - 40px);
}

#laravel_card{
    width: calc(100% - 40px);
}

@media screen and (max-width: 880px){
    #laravel_card{
        width: calc(90% - 40px);
    }
}

</style>