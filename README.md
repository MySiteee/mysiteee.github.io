<!DOCTYPE html>
<html>
 <head>
  <meta http-equiv="Content-Type" content="text/html"; charset="utf-8" />
  <meta name="description" content="Сайт созданный для себя. Здесь собраны все мои навыки." />
  <meta name="keywords" content="Всё, сайт, себе, для себя" />
  <link rel="stylesheet" type="text/css" href="First-style.css" />
  <title>Моя первая страничка</title>
 </head>
 <body>
  <h1 id="h1-first">Привет дружище!</h1>
  <a name="H2"></a>
  <h2 class="green">Это мой первый сайт</h2>
  <h1 id="h1-second">Привет дружище!</h1>
  <h1>Привет дружище!</h1>
  <p id="Start">Ну и <i>капец</i></p>
  <a href="#" class="href">А Я ССЫЛКА</a>
  <a href="#" class="href1">А Я ССЫЛКА</a>
  <p id="Norm">Не пугай!</p>
  <p class="LOL">Wow</p>
  <b class="GG">Wow</b>
  <p><u>ПРИВЕТ</u></p>
  <p><em>ПРИВЕТ</em></p>
  <p><strip>ПРИВЕТ</strip></p>
  <p><strike>ПРИВЕТ</strike></p>
  <p><strong>ПРИВЕТ</strong></p>

  <div id="Block1">Block1</div>
  <div id="Block2">Block2</div>
  <div id="Block3">Block3</div>
  <div id="StartBlock">Сверху</div>
  <div id="Add"> А сейчас реклама!</div>

  <small>Маленький</small>
  <big>Большой</big>

  <p>АА            АА</p>
  <pre>АА              АА</pre>

  <blockquote>Отступ справа и слева!!!</blockquote>
  <p align="right">ТЕКСТ СПРАВА</p>
  <p align="center">ТЕКСТ ПО ЦЕНТРЕ</p>
  <center>Текст По Центре2</center>
  <p>Кто-то что-то:<q>Ставит " хотя я не просил.</q></p>

  <nobr>ПИШЕТ ВСЁ В 1 РЯД</nobr>

  <ol>  //МОЖНО ЗАМЕНИТЬ 1 на A(ABC) или на любую букву ДЕЛАЕТ СПИСОК И САМО СТАВИТ 123 НА НАЧАЛЕ
    <li>Первый пункт</li>
    <li>Второй пункт</li>
    <li>Ну и 3 пункт</li>
  </ol>
  <ol type="1" start="4"> //СТАРТУЕТ НЕ С 123 А С 456
    <li>Первый пункт</li>
    <li>Второй пункт</li>
    <li>Ну и 3 пункт</li>
  </ol>
  <ol reversed="reversed"> //СТАРТУЕТ НАОБОРОТ НЕ С 123 А С 321
    <li>Первый пункт</li>
    <li>Второй пункт</li>
    <li>Ну и 3 пункт</li>
  </ol>
  <ul> //Малый отступ ЧАСТО используют
    <li>Первый пункт</li>
    <li>Второй пункт</li>
    <li>Ну и 3 пункт</li>
  </ul>
  <dir> //Большой отступ УСТАРЕЛ
    <li>Первый пункт</li>
    <li>Второй пункт</li>
    <li>Ну и 3 пункт</li>
  </dir>

  <a href="http://google.com">ОТКРЫВАЕТ ВМЕСТО ЭТОЙ ВКЛАДКИ</a>
  <hr />
  <a href="http://google.com" target="_blank">ОТКРЫВАЕТ В НОВОЙ ВКЛАДКЕ</a>
  <hr />
  <a href="http://google.com" target="_blank" title="Переход на ГУГЛ">ОТКРЫВАЕТ В НОВОЙ ВКЛАДКЕ И ПОКАЗЫВАЕТ ПРИ НАВЕДЕНИЕ КУРСОРА КУДА НАС ПЕРЕКИНЕТ</a>
  <hr />
  <a href="#H2">Перейти к ЭТО МОЙ ПЕРВЫЙ САЙТ</a>
  <hr />
  <a href="mailto:kirilldubchak@gmail.com">Email</a>
  <hr />

  <img src="https://img.discogs.com/OclFm7SLCnWi7U6ucNmOxOIzNfQ=/fit-in/600x600/filters:strip_icc():format(jpeg):mode_rgb():quality(90)/discogs-images/R-10639599-1501455206-5624.jpeg.jpg" width="200" height="200" />
  <img src="https://img.discogs.com/OclFm7SLCnWi7U6ucNmOxOIzNfQ=/fit-in/600x600/filters:strip_icc():format(jpeg):mode_rgb():quality(90)/discogs-images/R-10639599-1501455206-5624.jpeg.jpg" width="100" height="100" />
  <img src="https://img.discogs.com/OclFm7SLCnWi7U6ucNmOxOIzNfQ=/fit-in/600x600/filters:strip_icc():format(jpeg):mode_rgb():quality(90)/discogs-images/R-10639599-1501455206-5624.jpeg.jpg" width="100" height="100" align="right" /> Делает картинку справа
  <img src="https://img.discogs.com/OclFm7SLCnWi7U6ucNmOxOIzNfQ=/fit-in/600x600/filters:strip_icc():format(jpeg):mode_rgb():quality(90)/discogs-images/R-10639599-1501455206-5624.jpeg.jpg" width="100%" height="100%" title="Хреновая хрень!" alt="Хрень!" /> НА ВЕСЬ ЭКРАН, ПРИ НАВЕДЕНИЕ ЧТО ЭТО И ЕСЛИ В КОДЕ ОШИБКА ТО НАПИШЕТ "Хрень!"( из-за альт)

  <table border="1">
<caption>Таблица Чего-то</caption>
<tr>
<th>Что-то1</th>
<th>Что-то2</th>
<th>Что-то3</th>
</tr>
<tr><td>1</td><td>2</td><td>3</td></tr>
<tr><td>3</td><td>2</td><td>1</td></tr>
</table>

<hr />
<form name="test" action="" method="post">
  <label for="name2">Введи что хочешь:</label><input type="text" placeholder="Искать" name="name1" id="name2" title="Это поиск" maxlength="5" />
<br />
  <label for="Url2">Url:</label><input type="url" name="Url1" id="Url2" />
<br />
  <label for="male">Мужской:</label><input type="radio" name="state" id="male" />
<br />
  <label for="female">Женский:</label><input type="radio" name="state" id="female" />
<br />
  <label for="password">Введите пароль:</label><input type="password" name="password" id="password" />
<br />
  <input type="button" value="Отправить BUTTON" /> БЕЗ ПЕРЕЗАГРУЗКИ САЙТА
<br />
  <input type="submit" value="Отправить SUBMIT" /> С ПЕРЕЗАГРУЗКОЙ САЙТА
<br />
  <input type="reset" value="Очистить">
  <hr />
  <form action="" method="post">
  <p><strong>Введите ваш отзыв:</strong></p>
  <textarea rows="10" cols="45" name="text"></textarea>
  <button>Отправить</button>
</form>
  <hr />

  <select>
    <option>Ты нуб</option>
    <option>Ты рак</option>
    <option>Ты хак</option>
  </select>
<hr />

  <header>Шапка</header>
  <menu>
    <li>Что-то</li>
    <li>Как-то</li>
    <li>Где-то</li>
  </menu>
  <article>Статья, новость, пост...</article>
  <aside>Боковая панель</aside>
  <footer>Низ сайта</footer>
<hr />

  <article>
    <p>Песня</p>
    <audio controls="controls">
      <source src="https://dl2.mp3party.net/online/9427430.mp3" />
    </audio>
  </article>

  H<sub>2</sub>O
<br />
  4<sup>2</sup>
<hr />

  <details>
    <summary>Кто я?</summary>
    <p>Идиот</p>
  </details>
<hr />
  Выделяет <mark>текст</mark>
<hr />
  <ruby>
    C<rt>ccc</rt>
    @<rt>Sabaka</rt>
  </ruby>
<hr />
  <progress value="33" max="100">
    Загрузилось на <span id="value"></span>
  </progress>
<hr />
  <form oninput="result.value=(cm.value/2.54).toFixed(2)">
    <p>Введите длину в сантиметрах:
    <input type="number" name="cm" autofocus></p>
    <p>Длина в дюймах: <output name="result">0</output></p>
  </form>

  <p><abbr title="World Of Tanks">WoT</abbr></p>

  <address>Украина, Житомир</address>

  <hr /> //Делает горизонтальную линию

  <br /> //Продливает строчку вниз
  <br /> <br /> <br /> <br /> <br /> //Сильно продлевает сайт вниз

 </body>
</html>
