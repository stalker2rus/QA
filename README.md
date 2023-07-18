# Портфолио: инженер по тестированию

## Обо мне 

<img src="https://github.com/stalker2rus/QA/assets/57308100/9f454896-afbf-4ef5-98f0-d92d8790b940" width="150" >  <br>
Привет! Меня зовут Максим Худяков, я начинающий тестировщик. Но в ИТ можно сказать я уже более 10 лет, занимался сначала установкой глонасс мониторинга и видеонаблюдения. Потом перешёл в техподдержку этих же продуктов, а также системы электронный проездной с терминалами оплаты. Также в мои обязанности входило освоении новых видов оборудования для дальнейшего предложения клиентам. И вот сейчас решил освоить новую профессию с возможностью увеличения дохода и удалённой работы. <br>

В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.
<br>

## Навыки и технологии
``Jira``,``qase.io``,``SQL``,`` Postman``,``Sitechco``, ``Swagger``, ``Trello`` ``Macroscope`` , <br>
``SoapUI``, ``Confluencs``, ``Notion`` ``JSON``, ``Charles``, ``JMeter`` ``Wialon``, ``Chrome DevTools``.


## Проекты
<p> Проект 1: тест веб-приложения для учителей от Skyeng</p>
<p>Необходимо было провести тестирование:<p>
 <li>Функциональное</li>
 <li>API через “Postman”</li>
 <li>Приёмочное</li>
 <li>Smoke</li>
 <li>Регрессионное</li>
</ol>
<br>
Был разработан <a href=https://github.com/stalker2rus/QA/blob/main/%D0%A2%D0%B5%D1%81%D1%82%20%D0%BF%D0%BB%D0%B0%D0%BD.pdf)>тест план</a> оформлен в Confluence.  <br>
По нему было проведено тетирование, с использованием разных инструментов тестировщика. Таких как Postman, quse.io, sitechco и chrome devtools. Была собрана статистика и сотавлены багрепорты Jira по найденным багам. <br>
После был оформлен <a href="https://github.com/stalker2rus/QA/files/11881532/default.pdf">отчёт о тестировании итогового проекта</a> с заключение и рекомендациями, тоже в Confluence.
<br>
<br>
<br>
<p> Проект 2: написать RESTAPI запросы для тестирования веб-приложения Trello черз Postman</p>
<p>Необходимо было провести тестирование модулей:<p> 
✅ Доска. Используйте следующие методы:

- [Создание](https://developer.atlassian.com/cloud/trello/rest/api-group-boards/#api-boards-post)
- [Получение](https://developer.atlassian.com/cloud/trello/rest/api-group-boards/#api-boards-id-get)
- [Удаление](https://developer.atlassian.com/cloud/trello/rest/api-group-boards/#api-boards-id-delete)

✅ Списки. Используйте следующие методы:

- [Создание](https://developer.atlassian.com/cloud/trello/rest/api-group-lists/#api-lists-post)
- [Получение](https://developer.atlassian.com/cloud/trello/rest/api-group-lists/#api-lists-id-get)

✅ Карточки. Используйте следующие методы:

- [Создание](https://developer.atlassian.com/cloud/trello/rest/api-group-cards/#api-cards-post)
- [Удаление](https://developer.atlassian.com/cloud/trello/rest/api-group-cards/#api-cards-id-delete)
- [Изменение названия](https://developer.atlassian.com/cloud/trello/rest/api-group-cards/#api-cards-id-put) (поле name)
- [Смена списка](https://developer.atlassian.com/cloud/trello/rest/api-group-cards/#api-cards-id-put) (аналогично перетаскиванию из одной колонки в другую — поле idList)
- [Получение информации](https://developer.atlassian.com/cloud/trello/rest/api-group-cards/#api-cards-id-get)
- [Добавление комментария к карточке](https://developer.atlassian.com/cloud/trello/rest/api-group-cards/#api-cards-id-actions-comments-post)

Для этого была создана Postman <a href="https://github.com/stalker2rus/QA/blob/main/trello.postman_collection.json">коллекция</a>, которую можно запускать автоматически просто подставив "свежий" token.
<br>
<br>
<br>
<p> Проект 3: написать нагрузочный тест веб-сайта httpbin.org/post ипользуя Apache JMeter</p>

<p>Требования к вашему нагрузочному тесту:</p>

<li>параметры ``vu``, ``loop`` и ``ramp-up`` должны передаваться через командную строку</li>
<li>отчет по НТ формируется в папку web</li><br>
<p>для ответов от сервера применяются проверки:</p>
   <li>статус-код == 200</li>
    <li>в теле ответа значение поля `json.user` == 'jmeter'</li>
<br>
Для этого была создан <a href="https://github.com/stalker2rus/QA/blob/main/httpbin.jmx">JMX-файл</a> для запуска через Apache JMeter.

## Контактная данные
Email: stalker2rus@gmail.com <br>
Telegram: <a href=https://t.me/stalker2rus>@stalker2rus</a>

