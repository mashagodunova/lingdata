!doctype html>

<!-- так в HTML обозначаются комментарии. Выше вы видите объявление типа документа (DOCTYPE), так браузер понимает, что код ниже нужно интерпретировать как html -->

<html >

<!-- зона заголовка html, тег <title> - строка, которую браузер отображает на вкладках над страницами, <meta> и <link> сообщают технические сведения для браузера, например, что файл имеет кодировку Юникод (utf-8) -->

	<head>
		<title>Личная страница Марии Годуновой</title>
	 	<!-- Required meta tags -->
	 	<meta charset="utf-8">
	 	<meta name="viewport" content="width=device-width, initial-scale=1">

		<meta name="description" content="Личная страница и контакты">

		<!-- Bootstrap Core CSS -->
		<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet" media="screen">
<!-- Эта страница сделана с помощью bootstrap - популярной библиотеки для создания и настройки сайтов. Ниже вы увидите, что многие теги содержат атрибуты class - bootstrap содержит шаблоны, как такие элементы красиво оформить -->

	</head>
	
<!-- body - главная, содержательная часть страницы. Контент на этой странице делится на меню (nav), "шапку" (header), "подвал" (footer) и все остальное (мы заключили остаток в тег section) -->	
	<body>

<!-- меню (navigation bar) -->

		<nav id="mainNav" class="navbar navbar-default navbar-fixed-top navbar-custom">

<!-- div - это контейнеры - коробочки с текстом и/или графикой, которые можно вкладывать друг в друга. Пристально смотреть на теги в этой части кода не нужно -->
			<div class="container"> 
				<div class="navbar-header"> 
					<a href="https://ling.hse.ru/" class="navbar-brand">Школа лингвистики НИУ ВШЭ</a> 
				</div> 
				<nav class="collapse navbar-collapse" id="bs-navbar"> 
					<ul class="nav navbar-nav navbar-right"> 
						<li> <a href="https://lingvocodes.github.io/HSEinfo/ba-ling-2021/index.html">Страница курса</a> </li> 
						<li> <a href="https://lingvocodes.github.io/HSEinfo/ba-ling-2021/latin_2.html">Страница группы</a> </li> 
<!-- поправьте номер группы в URL, если нужно (от 1 до 4) -->
					</ul>
				</nav> 
			</div>
		</nav>

<!-- начинается шапка. у тега header есть атрибут style, который задает цвет фона и отступы. поменяйте значения атрибутов и посмотрите, как изменится страница -->

		<header style="background-color:Khaki; padding-top:70px; "> 
			<div class="container"> 
				<div class="row">
					<div class="col-md-4">
						<br><br>
<!-- здесь и дальше нужно поменять весь содержательный текст, чтобы получилась ваша личная страница -->
						<h1>Мария Годунова</h1>
						<hr> <!-- это горизонтальная линия -->
						<p><i>У тебя-своя сказка</i>, а у меня-<b>своя</b></p> 
					</div>
					<div class="col-md-4">
<!-- img - тег для вставки изображений. Мы использовали атрибут style, чтобы задать размер изображения и ширину рамки-->
<!-- Измените URL на URL вашей фотографии, а также настройте размер изображения -->
<img src="https://sun9-21.userapi.com/impg/JCi5b_CkqgX2SfLNI5QxbS89n89nDKl0Nfk2RA/vtW3TpoGl_Y.jpg?size=1200x1600&quality=96&sign=d09e86ee375fa0aab9f5d962f626ca68&type=album" style="height:500px; margin:20px 20px 40px 20px; " >
					</div>
				</div>
			</div>
		</header>

<!-- часть страницы, которая под шапкой -->
		<section style="background-color:Aquamarine; padding-top:70px; " id="portfolio">
			<div class="container">

<!-- атрибут col-md-... говорит, что контент будет разделен на несколько столбцов, их ширина соотносится как 3 - 6 - 3 (Bootstrap использует воображаемую сетку из 12 равных по ширине колонок) -->
				<div class="col-md-3">

<!-- <article> не влияет на оформление, но помогает структурировать контент на осмысленые разделы -->
					<article style="background-color:Aquamarine; padding-top:70px; ">
						<h3> <b>Место учебы</b></h2>
						<p>Фундаментальная и прикладная лингвистика, НИУ ВШЭ, Москва</p>
					</article>
					<article style="background-color:Aquamarine; padding-top:70px; ">
						<h3> <b>Родной город</b></h2>
						<p>Ростов-на-Дону</p>
					</article>
					<article style="background-color:Aquamarine; padding-top:70px; ">
						<h3><b>Школа</b></h2>
<!-- когда будете менять текст, не используйте бюрократических слов типа ГБОУ СОШ, ну пожаалуйста -->
						<p>Гимназия № 25</p>
					</article>
				</div>

				<div class="col-md-6">
					<article style="background-color:Aquamarine; padding-bottom: 110px;
						<h3> <b> <s>Интересная</s> информация обо мне</b></h2>
						<p>Я:<br>
						<p><li>Мечтала поступить на ОП "Фундаментальная и компьютерная лингвистика" во ВШЭ с 8 класса</li> <br>
						<li>В свободное время смотрю фильмы и пишу на них рецензии, которых у меня сейчас уже 127 штук </li><br>
						<li>Диджей,выступала уже на 23 мероприятиях в родном городе</li><br>
						<li>Занималась олимпиадами, но не смогла выиграть заключительный этап ВсОШ по русскому языку</li> <br>
						<li>Несмотря на это,<b> поступила</b> во ВШЭ благодаря перечневым олимпиадам и результатам ЕГЭ</li><br>
						<b><p><i>Предпочтения:</i></b> <br>
						<li>Учёба</li><br>
						<li>"Сто лет одиночества" Габриэля Гарсиа Маркеса</li><br>
						<li>Стулья <b>со спинкой</b></li><br>
						<li>Инди-фильмы</li><br>
				
						<p><b><i> А вот это не люблю:</i></b><br>
						<li>Лениться</li><br>
						<li>Разговоры <b>с оператором</b></li><br>
						<li>Молоко</li><br>
						<li>Холодец</li><br>
						<li><a href="https://www.urbandictionary.com/define.php?term=pick%20me%20girl">"Pick me girl" </a></li><br>
					</article>
					
				</div>

				<div style="background-color:Aquamarine; padding-top:0px; " class="col-md-3">
					<h3 style="background-color:Aquamarine; padding-top:70px; "> <b>Я в соцсетях </b> </h3>
<!-- тег <ul> - unordered list. Еще бывает тег <ol> -->
					<ul style="background-color:Aquamarine; padding-top:30px; ">
						<li>VK:<a href="https://vk.com/chtoianesu">https://vk.com/chtoianesu </a></li>
						<li>Instagram:<a href="https://www.instagram.com/noisee.pollution/">noisee.pollution</a></li>
					</ul>
					<div class="col-md-4">
<!-- img - тег для вставки изображений. Мы использовали атрибут style, чтобы задать размер изображения и ширину рамки-->
<!-- Измените URL на URL вашей фотографии, а также настройте размер изображения -->
<img src="https://sun9-88.userapi.com/impg/WY0jdS46b5TuDRdI_0GySVlzoNk2BxLq8Fs2cw/azITQPlnP2E.jpg?size=749x769&quality=96&sign=6f1b703368bf918c966a08f56fab1488&type=album" style="height:300px; margin:20px 20px 40px 20px; " >
					</div>
				</div>
			</div>
		</section>

<!-- это подвал. В этой части страницы обычно ставят копирайт (с помощью символа &copy;) и пишут об истории создания страницы. Поставьте свой копирайт -->
		<footer style="background-color:Aquamarine; padding-top:70px; " class="bs-docs-footer"> 
			<div class="container"> 
				<p style="text-align:right; ">&copy; М.Годунова, 2021</p> 
			</div>
		</footer>
	</body>
</html>
