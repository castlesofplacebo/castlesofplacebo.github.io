# Лабораторные работы по web-программированию

*Выполнила студентка ФИТИПа Шелудченко Анна Демьяновна (M33011)*

## Лабораторная работа №1

Данная лабораторная подразумевает создание макета сайта без использования знаний CSS, только HTML. Создаем сайт резюме -
портфолио. Главная задача данной лабораторной работы - ознакомиться с наиболее значимыми тегами и правилами их
использования.
<details>
  <summary>Ход работы</summary>

1. [x] Установить любой текстовый редактор или же специализированное ПО
   (WebStorm и так далее) - на ваш выбор.
2. [x] Определиться с темой проекта и нарисовать макет вашего сайта (схематично) - расположение картинок, текста, поля
   контактов и т.д. - картинку также положить в репозиторий (Можно фотографию рисунка на листочке)
   ![web-42](https://user-images.githubusercontent.com/71404543/134245541-9ef18278-0b46-459d-ab29-94d37b88ead9.jpg)
3. [x] Задать кодировку страницы UTF-8
4. [x] Описать ключевые слова в метаинформации страницы, а также в описании страницы
5. [x] Для упрощения проектирования подключить файл стилей outlines.css (опционально)
6. [x] Приступить к написанию сайта:
    * [x] Добавить Doctype
    * [x] Добавить теги ```<html>```,```<head>``` и ```<body>```,
    * [x] Установить язык для сайта-русский
    * [x] Добавить заголовок страницы
    * [x] Убедиться что в README.md указано ваше ФИО и номер группы, добавить в выбранную тему.
    * [x] Выделить логические элементы вашего сайта с помощью тегов:
        * main
        * header
        * footer
    * [x] Использовать теги section, nav, article, aside, h1-h6, p - согласно их предназначению. (смотреть лекцию)
    * [x] Использовать теги перечисления (ul, ol) (например, для описание ваших успехов или неуспехов).
    * [x] Вставить блок с псевдографикой из символов ASCII
    * [x] Вставить snippet кода, оформив его соответствующими тегами.
    * [x] Добавить цитату и формулу вашего успеха (желательно использовать тэги sub и sup).

Для выделения наиболее важных моментов использовать strong и b, em и i, del и ins
</details>

## Лабораторная работа №2

Цель лабораторной - научиться создавать и привязывать стили для элементов HTML. Про размещение элементов пока можно не
думать, необходимо достичь эффекта, при котором отдельно взятый элемент смотрится законченным, красивым и приятным
глазом. При этом вместе эти элементы не пестрят разными красками. Также необходимо определиться со стилистикой сайта.
Например: https://color.adobe.com/ru/

<details>
<summary>Ход работы</summary>

1. [x] Создать и подключить собственный файл стилей
2. [x] Добавить стили всем элементам на странице (границы - отступы).
3. [x] Должны быть использованы различные по типу селекторы. (Желательно по какой-либо конкретной методологии, например
   БЭМ)
4. [x] Добавить картинки.
5. [x] Определить цвета заливки и теней для элементов
6. Применить стили для текста, задать свойства:
    * [x] размера шрифта
    * [x] высоты строки
    * [x] семейство используемых шрифтов
    * [x] насыщенность шрифта
    * [x] выравнивание текста (горизонтальное, вертикальное)
    * [x] фон и цвет текста
    * [x] отступы
    * [x] пробелы
    * [x] стилизация переформатированного текста
    * [x] подчеркивание, зачеркивание и другие
    * регистр символов

</details>

## Лабораторная работа №3

Произвести выравнивание всех ранее описанных элементов вашего сайта используя удобный для вас способ - флексы или флоты,
либо применить 12-ти столбчатую вёрстку. Обязательное наличие горизонтальных и вертикальных рядов элементов. Если у вас
до этого не было - всегда можно добавить (например, галерею с картинками). Также необходимо проработать то, как ваш
макет будет выглядеть на различных мониторах (на маленьком ноутбуке, полноценном Full HD, 2K монитор).

<details>
<summary>Ход работы</summary>

1. [x] Выбрать элементы, которые не будут отображаться на маленьких мониторах, например, рекламный баннер во всю длину
   footer’a. Использовать css-правила @media screen для скрытия элементов не умещающихся в клиентскую область.
2. [x] Закрепить элемент с помощью абсолютного позиционирования - например строку меню либо шапку или подвал сайта.
3. [x] Добавить на страницу таблицу с заголовками и стилями для чётных и нечётных строк. В качестве типа отображения
   таблицы рекомендуется воспользоваться grid’ом, для достижения лучшей адаптивности. (т.е. необходимо добиться того,
   чтобы колонки таблицы изменяли свой размер в зависимости от размера окна).

</details>

## Лабораторная работа №4

Цель лабораторной работы – научится взаимодействовать со элементами и браузером используя встроенной скриптовой движок
JavaScript.
<details>
<summary>Ход работы</summary>

1. [x] Добавить новые страницы для вашего проекта, согласно пунктам меню в шапке сайта.
2. [x] Создать скрипт, который будет выполнятся на каждой странице, добавить его в отдельную папку и подключить в
   разделе ```<head>``` ваших страниц.
3. [ ] Используя IIFE, подписаться на события загрузки страницы и вывести в подвал статистическую информацию о скорости
   загрузки.
   ![image](https://user-images.githubusercontent.com/71404543/140092847-a587d3c1-694b-48c8-ab04-bbf203c929ae.png)
4. [ ] Добавить интерактивности меню, обработать события наведения мыши на конкретные пункты с использованием CSS либо
   JS.
5. [ ] В зависимости от того, на какой странице находится пользователь (можно понять по document.location)
   добавить соответствующему пункту меню CSS class, отвечающий за «активное» состояние (см. пример).
   ![image](https://user-images.githubusercontent.com/71404543/140092958-bab7fa23-e465-493e-8dbf-90f9f83f8d5f.png)

</details>