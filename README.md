# Основи програмування на JavaScript
## 1. Що таке JavaScript
JavaScript - це мова програмування високого рівня, що застосовується у своренні веб-додатків, веб-сервісів і організовує активну взаємодію з користувачем.
## 2. Підключення JavaScript до веб-сторінки
Ми можемо підключати JavaScript двома способами. Перший спосіб - це включення JavaScript коду безпосередньо в сторінку сайту. Для цього своріть азовий шаблон сторінки, який включає теги head, body. Тепер в середині тегу body в кінці додаємо тег `<script></script>`. Код наведений нижче. 
    
	<!DOCTYPE html>
	<html lang="en">
	<head>
		<meta charset="UTF-8">
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<title>Document</title>
	</head>
	<body>

		<script>
			alert("It is webpage!");
		</script>	
	</body>
	</html>
Дуже часто нам необхідно писати багато коду, тому розміщувати html, JavaScript в одному файлі не є раціональним рішенням. Що потрібно зробити? Створіть окремий файл з розширенням .JS. Наприклад, index.js. Підключіть файл JavaScript в `<head></head>` таким чином:
	
	<!DOCTYPE html>
	<html lang="en">
	<head>
		<meta charset="UTF-8">
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<title>Document</title>
		<script src="javascript.js"></script>
	</head>
	<body>
	</body>
	</html>
	
## 3. Типи даних
* var, let
