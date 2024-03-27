<!DOCTYPE html>
<html>

<head>
    <style>
        .container {
            border: 2px solid black;
            padding: 10px;
            margin: 10px;
            display: flex;
            flex-direction: column;
        }
        .container2 {
            border: 2px solid black;
            padding: 1px;
            margin: 1px;
            display: flex;
            flex-direction: column;
        }

        .centered {
            text-align: center;
            font-size: 2em;
        }

        .right-aligned {
            margin-left: auto;
            font-size: 1.5em;
        }

        .centered img {
            display: block;
            margin: 0 auto;
        }
    </style>
</head>

<body>
    <div class="container">
    <div class="container2">
        <div style="font-size: 2em;">Усім привіт!</div> <!-- Збільшення розміру шрифту у два рази -->
        <div class="centered">Мене звати <font color="red">Коцюбайло Віктор Іванович</font></div>
        <div class="right-aligned">Я студент групи <font color="red">ТЗ-21</font></div>
</div>
        <div>За <a href="https://developer.mozilla.org/en-US/">цим посиланням</a> ви зможете знайти цікаву інформацію про мову розмітки HTML5 та мову стилів CSS3</div>
        <div>А цю картинку я знайшов на просторах інтернету, і хотів би нею поділитися:</div>
        <div class="centered">
            <a href="https://kartinki.pics/pics/uploads/posts/2022-09/1662615787_1-kartinkin-net-p-milie-kotiki-v-shapochkakh-instagram-1.jpg">
                <img src="https://kartinki.pics/pics/uploads/posts/2022-09/1662615787_1-kartinkin-net-p-milie-kotiki-v-shapochkakh-instagram-1.jpg" alt="Це котик)" width="300" height="400">
            </a>
        </div>
        <div>Вона клікабельна, і якщо по ній клікнути то відкриється сайт де я взяв фото (там є ще фото з котиками :> (не реклама!))</div>
</div>
</body>

</html>
