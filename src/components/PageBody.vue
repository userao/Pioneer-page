<template>
  <main>
    <article id="about" class="item">
      <div class="article-body">
        <div class="article-description">
          <h2>О НАС</h2>
          <p>
            ПИОНЕР – научно-производственное предприятие,
            занимающееся разработкой и производством силовых машин.
            <br>
            <span class="blank"></span>
            За 27 лет на заводе сформирован мощный производственный
            потенциал - научно-технический центр, испытательная лаборатория,
            современная база, учебный центр и широкая сеть региональных
            и международных представительств. Сформирована широкая сеть
            региональных и международных представительств в Российской
            Федерации, Республике Беларусь, Узбекистане и Казахстане.
          </p>
        </div>
        <div class="article-images">
          <div class="article-image">
            <img src="../assets/images/about-us.png" alt="about us image">
          </div>
        </div>
      </div>
    </article>
    <article id="production" class="item">
      <div class="article-body">
        <div class="article-description">
          <h2>ПРОДУКЦИЯ</h2>
          <button class="download"><span>СКАЧАТЬ КАТАЛОГ</span></button>
        </div>
        <div class="article-images">
          <div class="article-image">
            <img src="../assets/images/production-gages.png" alt="gage">
            <p>Датчики и измерители<br>температуры</p>
          </div>
          <div class="article-image">
            <img src="../assets/images/production-turbine.png" alt="engine">
            <p>Газовая турбина</p>
          </div>
          <div class="article-image">
            <img src="../assets/images/production-calibrators.png" alt="turbine">
            <p>Калибраторы</p>
          </div>
        </div>
      </div>
    </article>
    <article id="geografy" class="item">
      <div class="article-body">
        <div class="article-description">
          <h2>ГЕОГРАФИЯ ПОСТАВОК</h2>
        </div>
        <div class="article-images">
          <div class="article-image">
            <img src="../assets/images/map.png" alt="RF map">
          </div>
          <div id="cities" class="article-image">
            <img src="../assets/images/cities-dots.png" alt="cities">
          </div>
          <div id="tomsk" class="article-image">
            <img src="../assets/images/tomsk-state.png" alt="Tomsk">
            <div id="modal">
              <p class="modal-text">
                г. Томск<br>
                ул. Мостовая<br>
                +7 (3822) 32-32-32
              </p>
            </div>
          </div>
        </div>
      </div>
    </article>
    <article id="cooperation" class="item">
      <div class="article-body">
        <div class="article-description">
          <h2>СОТРУДНИЧЕСТВО</h2>
          <p>
            В номенклатуре выпускаемой НПП «ПИОНЕР» продукции найдется все,
            что необходимо для успешного решения задачи автоматизации технологических
            процессов на любом предприятии. Все средства измерения производства «ПИОНЕР»
            внесены в Государственный реестр СИ и имеют необходимые разрешительные документы.
            <br>
            <span class="blank"></span>
            Ежегодно НПП «ПИОНЕР» реализует несколько проектов по модернизации серийных и
            разработке новых приборов, призванные в наибольшей степени удовлетворять
            возрастающие требования наших заказчиков.
          </p>
        </div>
        <div class="article-images">
          <div class="article-image">
            <img src="../assets/images/cooperation.png" alt="meeting">
          </div>
        </div>
      </div>
    </article>
  </main>
</template>

<script>

</script>

<style scoped>
  .item {
    overflow: auto;
    background: white;
  }
  .item:last-child {
    padding-bottom: 80px;
  }
  .blank {
    display: block;
    height: 1em;
  }
  .article-body {
    display: flex;
    justify-content: center;
    margin: 80px 165px 80px 165px;
  }
  .article-description {
    margin-right: 30px;
  }
  .article-description h2 {
    font-size: 50px;
    font-weight: 600;
    margin-bottom: 30px;
  }
  .article-description p {
    font-size: 25px;
    line-height: 30px;
  }
  #production .article-description {
    display: flex;
    justify-content: space-between;
  }
  #production .article-body {
    display: block;
  }
  .article-images {
    display: flex;
    justify-content: space-between;
  }
  .article-image {
    font-size: 20px;
    color: #1AA0FF;
  }
  .article-description span {
    font-size: 20px;
    color: #1AA0FF;
  }
  .download {
    background: none;
    border: none;
    margin-bottom: 40px;
  }
  .download span:after {
    content: "";
    width: 25px;
    height: 25px;
    background: url("../assets/images/download-logo.png");
    display: inline-block;
    margin-left: 10px;
  }
  .article-imageu > p {
    text-align: center;
  }
  #geografy .article-body {
    flex-direction: column;
  }
  #geografy .article-images {
    position: relative;
  }
  #cities {
    position: absolute;
    left: 31px;
    top: 160px;
  }
  #tomsk {
    position: absolute;
    top: 360px;
    left: 420px;
  }
  #modal {
    position: absolute;
    display: none;
    width: 200px;
    left: 100px;
    bottom: 70px;
    background: #1AA0FFB2;
  }
  .modal-text {
    color: black;
    font-size: 20px;
    font-weight: 700;
  }
  #tomsk:hover > #modal{
    display: block;
  }
</style>
