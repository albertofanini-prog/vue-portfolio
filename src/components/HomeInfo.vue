<template>
  <section class="home_section">
    <div class="home_section_pic">
      <img class="home_pic" alt="Vue logo" src="../assets/me/green_pic.png">
    </div>
    <div class="home_section_text">
      <h1 class="name">Alberto Fanini</h1>
      <p class="job">Jr. Full Stack Web Developer</p>
      <ul class="tecnologies_list">
        <li class="tecnologies_list_item">
          <img src="../assets/tecnologies/html.png" id="html" alt="">
        </li>
        <li class="tecnologies_list_item">
          <img src="../assets/tecnologies/css.png" id="css" alt="">
        </li>
        <li class="tecnologies_list_item">
          <img src="../assets/tecnologies/bootstrap.jpg" id="bootstrap" alt="">
        </li>
        <li class="tecnologies_list_item">
          <img src="../assets/tecnologies/js.png" id="js" alt="">
        </li>
        <li class="tecnologies_list_item">
          <img src="../assets/tecnologies/vue.png" id="vue" alt="">
        </li>
        <li class="tecnologies_list_item">
          <img src="../assets/tecnologies/sass.png" id="sass" alt="">
        </li>
        <li class="tecnologies_list_item" id="php_container">
          <img src="../assets/tecnologies/php_mysql.png" alt="">
        </li>
        <li class="tecnologies_list_item">
          <img src="../assets/tecnologies/laravel.jpg" id="laravel" alt="">
        </li>
      </ul>
      <p class="description">
        Nato ad Arezzo il 3 luglio del 1998, ho sempre avuto la passione per la tecnologia. <br>
        È una passione che ho iniziato a coltivare già dalla scuola media quando, scegliendo l'indirizzo informatico, ebbi modo di iniziare a utilizzare
        le varie tecnologie di base quali HTML e JS.<br>
        Stanco della solita vita monotona, a fine novembre 2021, decido di lasciare il tanto ambito posto fisso per intraprendere il corso
        formativo da Full Stack Web Developer con Boolean Careers.<br>
        Il corso mi ha fatto capire quanto per me questo settore sia stimolante, creativo e quanto mi invoglia a finalizzare le varie tecnologie e a impararne di nuove.<br>
        <br>
        Dopo questa breve presentazione ti do il benvenuto nel mio primo portfolio realizzato con VueJS e alcune tecnologie a lui integrabili.
      </p>
    </div>
  </section>
</template>

<script>
export default {
    
}
</script>

<style lang="scss">
.home_section{
  // width: 80%;
  // height: 100%;
  position: relative;
  display: flex;
  align-items: flex-start;
  justify-content: center;
  margin: 0;
  padding-top: 50px;
  .home_section_pic{
    width: 35%;
    display: flex;
    align-items: center;
    justify-content: flex-end;
    .home_pic{
      width: 70%;
      border-radius: 9999px;
    }
    @media screen and (max-width: 630px){
      width: 95%;
      justify-content: center;
    }
  }
  .home_section_text{
    width: 65%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    gap: 15px;
    .name{
      color: #42b983;
      font-size: 2.4rem;
      padding-bottom: 10px;
    }
    .job{
      color: #FFF;
      font-size: 1.4rem;
      padding-bottom: 10px;
    }
    .tecnologies_list{
    //   border: 3px solid orange;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-wrap: wrap;
      gap: 10px;
      width: 100%;
      padding-bottom: 20px;
      .tecnologies_list_item{
        width: 65px;
        height: 65px;
        #html, #css, #bootstrap, #js, #vue, #sass, #laravel{
          border-radius: 9999px;
          overflow: hidden;
        }
        img{
          width: 100%;
          height: 100%;
        }
      }
      #php_container{
        width: 125px;
      }
      @media screen and (max-width: 998px){
        width: 70%;
      }
      @media screen and (max-width: 668px){
        width: 60%;
      }
      @media screen and (max-width: 614px){
        width: 75%;
      }
      @media screen and (max-width: 491px){
        width: 60%;
      }
      @media screen and (max-width: 377px){
        width: 100%;
      }
    }
    .description{
      color: #FFF;
      width: 75%;
      text-align: center;
      font-size: 1.2rem;
      padding-bottom: 25px;
      @media screen and (max-width: 630px){
        text-align: center;
      }
      @media screen and (max-width: 630px){
        width: 90%;
      }
    }
    @media screen and (max-width: 630px){
      width: 95%;
    }
  }
  @media screen and (max-width: 630px){
    // width: 80%;
    // height: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    margin: 0;
  }
}
</style>