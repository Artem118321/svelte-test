<svelte:head>
    <title>Тур-агентство</title>

</svelte:head>

<b><p>Тур-агентство</p></b>
<header class="header">
    <img class="header-logo" src="/svelte-test/img/1.webp"  alt="" width="200px" height="100px">
</header>
<body>

<b><p>Доступные туры</p> </b>
<div class="row">

    <div class="column">
        <div class="centr">
            
            <img alt="The project logo" src={logo} />
        </div>
      <div class="card"><a href="/">Тенерифе, Испания</a> <br>
        Это самое популярное курортное место в составе Канарских островов Испании. Тенерифе омывается водами Атлантического океана, и круглый год температура воздуха здесь не опускается ниже +21 ⁰С.</div>
    </div>
    <div class="column">
        <div class="centr">
            <img style="text-align: center;"  src="/svelte-test/img/2.webp" alt="background_image" height="120px" width="100px">
        </div>
      <div class="card"><a href="/">Сен-Тропе, Франция</a> <br>
        В список самых известных курортов Европы входит Сен-Тропе на Лазурном Берегу Франции. Небольшой элитный город находится на побережье Средиземного моря.</div>
    </div>
    <div class="column">
        <div class="centr">
            <img style="text-align: center;"  src="/svelte-test/img/3.webp" alt="background_image" height="120px" width="100px">
        </div>
      <div class="card"><a href="/">Пафос, Кипр</a> <br>
        Самый дорогой курорт на острове Кипр популярен среди туристов. Здесь расположены лучшие пятизвёздочные отели, престижные рестораны и пляжи.</div>
    </div>
      </div>
      
      <div class="row">
        <div class="column">
            <div class="centr">
                <img style="text-align: center;"  src="/svelte-test/img/4.webp" alt="background_image" height="120px" width="100px">
            </div>
          <div class="card"><a href="/">Рио-де-Жанейро, Бразилия</a>  <br>
            На крупном оживлённом курорте находятся лучшие пляжи Бразилии: Копакабана, Леблон и Ипанема.</div>
        </div>
        <div class="column">
            <div class="centr">
                <img style="text-align: center;"  src="/svelte-test/img/5.webp" alt="background_image" height="120px" width="100px">
            </div>
          <div class="card"><a href="/">Маэ, Сейшельские Острова</a> <br>
            Здесь находится столица Виктория и более 60 песчаных пляжей с белым песком и тропической растительностью.</div>
        </div>
        <div class="column">
            <div class="centr">
                <img style="text-align: center;"  src="/svelte-test/img/6.webp" alt="background_image" height="120px" width="100px">
            </div>
          <div class="card"><a href="/">Гранд-Бэй, Маврикий</a> <br>
            К самым живописным курортам Маврикия относится небольшой город Гранд-Бэй, расположенный в бухте на севере острова.</div>
        </div>
          </div>
</body>
<script>
	import logo from "/svelte-test/img/11";
</script>

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
  
  img {
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
  

  

  

          </style>