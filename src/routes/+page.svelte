<svelte:head>
    <title>Тур-агентство</title>

</svelte:head>

<b><p>Тур-агентство</p></b>
<header class="header">
    <img class="header-logo" src="/svelte-test/img/1.webp"  alt="" width="200px" height="100px">
</header>
<b><p>Доступные туры</p> </b>
<div class="row">

    <div class="column">
        <div class="centr">
            <img style="text-align: center;"  src="/svelte-test/img/11.webp" alt="" height="120px" width="100px">
        </div>
      <div class="card"><a href="/">Тенерифе, Испания</a> <br>
        Это самое популярное курортное место в составе Канарских островов Испании. Тенерифе омывается водами Атлантического океана, и круглый год температура воздуха здесь не опускается ниже +21 ⁰С.</div>
    </div>
    <div class="column">
        <div class="centr">
            <img style="text-align: center;"  src="/svelte-test/img/2.webp" alt="" height="120px" width="100px">
        </div>
      <div class="card"><a href="/">Сен-Тропе, Франция</a> <br>
        В список самых известных курортов Европы входит Сен-Тропе на Лазурном Берегу Франции. Небольшой элитный город находится на побережье Средиземного моря.</div>
    </div>
    <div class="column">
        <div class="centr">
            <img style="text-align: center;"  src="/svelte-test/img/3.webp" alt="" height="120px" width="100px">
        </div>
      <div class="card"><a href="/">Пафос, Кипр</a> <br>
        Самый дорогой курорт на острове Кипр популярен среди туристов. Здесь расположены лучшие пятизвёздочные отели, престижные рестораны и пляжи.</div>
    </div>
      </div>
      
      <div class="row">
        <div class="column">
            <div class="centr">
                <img style="text-align: center;"  src="/svelte-test/img/4.webp" alt="" height="120px" width="100px">
            </div>
          <div class="card"><a href="/">Рио-де-Жанейро, Бразилия</a>  <br>
            На крупном оживлённом курорте находятся лучшие пляжи Бразилии: Копакабана, Леблон и Ипанема.</div>
        </div>
        <div class="column">
            <div class="centr">
                <img style="text-align: center;"  src="/svelte-test/img/5.webp" alt="" height="120px" width="100px">
            </div>
          <div class="card"><a href="/">Маэ, Сейшельские Острова</a> <br>
            Здесь находится столица Виктория и более 60 песчаных пляжей с белым песком и тропической растительностью.</div>
        </div>
        <div class="column">
            <div class="centr">
                <img style="text-align: center;"  src="/svelte-test/img/6.webp" alt="" height="120px" width="100px">
            </div>
          <div class="card"><a href="/">Гранд-Бэй, Маврикий</a> <br>
            К самым живописным курортам Маврикия относится небольшой город Гранд-Бэй, расположенный в бухте на севере острова.</div>
        </div>
          </div>

          <footer>
            <hr>
            Соликамск, 2024 <br>
            Игнатов Артём ИСП-2
          </footer>

          <style>
            .row {
    box-sizing: border-box;
    display: flex;
  place-items: center;
  }
  
  .centr{
  display: grid;
  place-items: center;
  }
  
  .column {
  margin-top: 25px;
  margin-bottom: 20px;
  margin-left: 30px;
  margin-right: 40px;
    width: 25%;
    padding: 0 10px;
  }
  
  .row:after {
    content: "";
    display: flex;
    clear: both;
  }
  
  .card {
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
    padding: 16px;
    text-align: center;
    background-color: lightgreen;
    color: black;
    border-radius: 10px;
  }
  
  @media screen and (max-width: 600px) {
    .column {
      width: 100%;
      display: block;
      margin-bottom: 20px;
    }
  }
  
      body {
      padding: 0;
      width: 100%;
      background-color: white;
      font-size: 20px;
      }
      
  .header .header-logo img {
      width: 200px;
  }
  
  p{
      text-align: center;
  }

  div img  {
    border-radius: 5px;
    height: 230px;
  width: 100%;
  }
  
  img, svg {
      vertical-align: middle;
  }

  .header .header-logo img:nth-child(2) {
      position: absolute;
      top: 0;
      left: 0;
      opacity: 0;
  }
  
   b{
    text-align: center;
   }
  
  a{
    text-decoration: none;
  }

  a:hover{
    color: white;
  }
  
  .info{
      text-align: center;
      position: relative;
  }
  
  .info-container{
      height: 100%;
  
  }
  
  .container{
      display: flex;
      max-width: 1400px;
      margin: 190px 0 0 2.5rem;
  }
  
  .info h1{
      font-size: 4rem;
      margin: 0;
  }
  
  .info h1 p{
      position: relative;
      font: inherit;
      margin: 0;
      text-align: left;
      line-height: 130%;
      width: fit-content;
      font-weight: 800;
      letter-spacing: -0.03em;
  }
  
  .info h2{
      max-width: 65ch;
      font-weight: 200;
      margin-top: 0.50rem;
  }
  
  
  .info .info-text{
      position: relative;
  }
  
  .scroll-button{
      display: flex;
      border: none;
      outline: none;
      cursor: pointer;
  }
  
  .scroll-button .arrow{
  margin-left: 0.50rem;
  }
          </style>