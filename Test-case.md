# Тест кейсы
#### ID: 1
	Title: Заполнить поле Name
	Steps: 
	1. Выбрать поле Name
	2. Ввести валидное имя
	Expected result: Имя введено
#### ID 2
	Title: Заполнить поле Email
	Steps:
	1. Выбрать поле Email
	2. Ввести валидный email
	Expected result: Email введен
#### ID 3
	Title: Заполнить поле Password
	Steps:
	1. Выбрать поле Password
	2. Ввести валидный пароль
	Expected result: Пароль введен
#### ID 4
	Title: Заполнить поле Surname
	Steps:
	1. Выбрать поле Surname
	2. Ввести валидные данные
	Expected Result: Фамилия введена
#### ID 5
	Title: Отправить форму
	Pre-conditions:
	Заполнить форму валидными данными
	Steps:
	1. Нажать на кнопку [Submit]
	Expected result: Форма успешно отправлена
#### ID 6
	Title: Отправить форму с незаполненным полем Surname
	Pre-conditions:
	Заполнить все поля валидными данными, кроме Surname
	Steps:
	1. Нажать на кнопку [Submit]
	Expected result: Форма успешно отправлена
#### ID 7
	Title: Пустое поле Name
	Pre-conditions: Заполнить все поля, кроме Name
	Steps:
	1. Выбрать поле Name
	2. Ничего не вводить
	3. Перейти к другому полю
	Expected result: Поле обвелось красной рамкой. Появился pop-up с сообщением  “This field is required”
#### ID 8
	Title: Пустое поле Email
	Pre-conditions: Заполнить все поля, кроме email
	Steps:
	1. Выбрать поле Email
	2. Ничего не вводить
	3. Перейти к другому полю
	Expected result: Поле обвелось красной рамкой. Появился pop-up с сообщением  “This field is required”
#### ID 9
	Title: Пустое поле Password
	Pre-conditions: Заполнить все поля, кроме Password
	Steps:
	1. Выбрать поле Password
	2. Ничего не вводить
	3. Перейти к другому полю
	Expected result: Поле обвелось красной рамкой. Появился pop-up с сообщением  “This field is required”
#### ID 10
	Title: Отправить форму с пустыми полями
	Steps:
	1. Нажать на кнопку [Submit]
	Expected result: Появляется сообщениие об ошибке "Error: All Fields are Required". Обязательные поля подсвечиваются красным
