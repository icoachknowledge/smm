---
title: Настройка рекламы в Facebook Business
category: Настройка рекламы
order: 1
---

Выдача задания
--------------

#### В задании обязательно должны быть:

* Ссылка на лендинг коуча
* Целевое действие: оставил заявку или подтвердил подписку
* Ссылка на страницу «Спасибо», которая открывается сразу после целевого действия
* Ссылка на группу коуча в FB
* Ссылка на файл с концепцией. В ней описание ца, обязательны: возраст, пол, регион, язык целевой аудитории.
* Есть ли какие-то заранее собранные базы клиентов коуча для lookalike
* Ссылка на папку «Креатив» с шестью баннерами для объявлений
* Финансовый лимит для этой рекламной кампании

#### У тебя должен быть доступ:

* Ко всем гугл докам и папкам, ссылки на которые тебе прислали
* В рекламный кабинет коуча
* Advertiser доступ к группе коуча в FB

Проверь страницу «Спасибо»
--------------------------

#### Требования

\[\] Удалось оставить тестовую заявку на лендинге без ошибок

\[\] После заявки попал на тот же адрес страницы «Спасибо» совпадал с заявленным адресом в ТЗ

\[\] Страница «Спасибо» открылась сразу после выполнения целевого действия

#### Инструкция

* Заходишь на ленд коуча. Нажимаешь «Записаться на бесплатную консультацию».
* Вводишь свое имя, имейл/телефон, жмешь «Записаться».
* Попадаешь на страницу «Спасибо», копируешь адрес
* Если ты попал на страницу «Подтвердите подписку», ты заходишь в свой имейл
* Подтверждаешь подписку, попадаешь на страницу «Спасибо», копируешь ее адрес
* Проверяешь, что адрес страницы «Спасибо» соответствует адресу, указанному в ТЗ

Проверь работоспособность пикселя на странице «Спасибо»
-------------------------------------------------------

#### Требования

\[\] Pixel ID: 1733822553334542 на странице «Спасибо».

\[\] Наличие события “Lead”.

#### Инструкция

* Открываешь «Спасибо» в браузере Google Chrome.
* В правом верхнем углу \- синий значок Facebook Pixel Helper с цифрой 3.
* Если это приложение не установлено, устанавливаешь по ссылке [https://chrome.google.com/webstore/detail/facebook-pixel-helper/fdgfkebogiimcoedlicjlajpkdmockpc?hl=en](https://www.google.com/url?q=https://chrome.google.com/webstore/detail/facebook-pixel-helper/fdgfkebogiimcoedlicjlajpkdmockpc?hl%3Den&sa=D&ust=1518769283475000&usg=AFQjCNEVdrmfGThfSONu7LbRD1Q5eIcScw)
* Кликаешь по значку, убеждаешься, что Pixel ID: 1733822553334542.
* Убеждаешься, что под Pixel ID есть раздел Lead с зеленой галочкой

![](images/image4.png)

Если Pixel ID не такой или нет события Lead, пишешь Project Менеджеру, что не принимаешь ТЗ и останавливаешь настройку.

Рекламная кампания
------------------

* Открываешь рекламный кабинет [https://www.facebook.com/ads/manage/powereditor](https://www.google.com/url?q=https://www.facebook.com/ads/manage/powereditor&sa=D&ust=1518769283476000&usg=AFQjCNFUzSpT0HnD1Pcrf_TcBJrIfT7CEg)

* Нажимаешь кнопку Create Campaign. Выбираешь Use Guided Creation
* В левом столбце у тебя описаны три этапа настройки рекламы: Campaign (настройка кампании), Ad Set (настройка аудитории), Ad (настройка объявлений).

1\. Раздел Campaign
-------------------

### Цель рекламной кампании

Objective - Conversions.

* В разделе What is your marketing objective? Выбираешь столбец Сonversion, тыкаешь Conversions

### Название РК и Key Result

Название кампании должно быть по такой формуле:

* Conversions
* дата латиницей без пробела

Пример: Conversions 28nov

Key Result: Leads

#### Инструкция

* В цели рекламной кампанииKey Result открываешь выпадающий список Select the action you most want to measure
* Нажимаешь, выбираешь в списке Leads

### Настройки аккаунта

* Страна Россия
* Валюта Российский рубль
* Временная зона Москва

![](images/image3.png)

2\. Раздел Ad Set
-----------------

### Ad Set Name

### 2.1. Подраздел Conversion

#### Инструкция

* В графе Conversion выбираешь Lead

![](images/image2.png)

### 2.2. Подраздел Audience

#### Аудитория:

* Ты настраиваешь 3 разные аудитории

* Location, Age, Gender, Language в концепции
* Detailed Targeting - настраиваешь на интересы, которые соответствуют интересам ЦА. Если есть собранные базы клиентов, то еще и по lookalike этих баз.

#### Инструкция

* Читаешь внимательно документ «Концепция».
* Ознакамливаешься с тренером и аудиторией на лендинге.
* Вводишь Location, Age, Gender, Language (в концепции).
* Заполняешь пункт Detailed Targeting.
* Ставишь галочку в Expand interests when it may increase conversions at a lower cost per conversion.

Пример региона: Russia (всегда), European Economic Area, North American Free Trade Agreement, Asia-Pacific Economic Cooperation, СНГ не выбираешь.

Если в концепции не указаны пол, возраст, регион, язык, ты не пытаешься додумать это самостоятельно или сделаешь как нибудь. Вместо этого ты сообщаешь об этом Project Менеджеру и ждешь эту инфу.

### 2.3. Подраздел Budget&Schedule

Lifetime Budget — 2000 rub

Schedule — 5 суток с момента настройке

Optimization for Ad Delivery — Conversions

Conversion window - AFTER CLICKING AD - 1 day click

### 2.4. Ad Set Name

Название Ad Set должно быть по формуле:

* Короткое значимое до 5 букв название аудитории латиницей
* Регион
* Возраст

Пример: biz - W - 25+

Где biz - бизнесмены.

#### Инструкция

* После установления бюджета возвращаешься наверх к Ad Set Name.
* У тебя автоматом там уже есть регион и возраст.
* Перед регионом указываешь название аудитории.

3\. Раздел Ad
-------------

### 3.1. Подраздел Identity

 Ad Name должно быть по формуле:

* название аудитории (biz)
* подчёркивание «_»
* название текста (ad1)
* подчёркивание «_»
* название картинки (pic1)

Пример: biz\_ad1\_pic1

Facebook Page - группу коуча в FB.

### 3.2. Подраздел Format

Картинки в папке «Креатив».

#### Инструкция

* Выбираешь вид Single Image.
* Открываешь папку «Креатив» с баннерами, скачиваешь их.
* Сверяешь размер картинок с нужными параметрами, они описаны в этом подразделе «Images».
* Если они весят больше, заходишь на [http://compressjpeg.com/](https://www.google.com/url?q=http://compressjpeg.com/&sa=D&ust=1518769283482000&usg=AFQjCNGmhOBFdXlnJfxXMDALvV1g9iowIQ)
* Заливаешь туда баннеры (копируешь и переносишь в поле Drop your files here).
* Сервис сжимает эти картинки, нажимаешь Download All.
* Проверяешь опять, что эти баннеры нужного размера.
* Возвращаешься к Images, нажимаешь Upload Images, загружаешь все баннеры.

### 3.3. Подраздел Links

* #### Website Url
    

Website Url пишем по формуле:

* ссылка на сайт автора (страница записаться)
* утм метка

#### Утм метка

Утм метку создаем по формуле:

* адрес сайта автора
* «?utm_source=fb-ad»
* «&utm_campaign=»\+ сегодняшняя дата (она же в дате РК)
* «&utm_content=»\+ название объявления (biz\_ad1\_pic1)

Пример Website Url: [http://elvirahellmann.icoach.io/?utm\_source=fb-ad&utm\_campaign=28nov&utm\_content=biz\_ad1_pic1](https://www.google.com/url?q=http://elvirahellmann.icoach.io/?utm_source%3Dfb-ad%26utm_campaign%3D28nov%26utm_content%3Dset1ad1pic1&sa=D&ust=1518769283484000&usg=AFQjCNF6y8rwOBztMld-hxxEEfkloYlsjg)

* #### Headline
    

Headline - текст на кнопке на лендинге коуча.

Text - текст с первого экрана лендинга коуча.

Call to action - Learn More.

Text должен выглядеть так:

* Заголовок без точки
* Пустая строка
* Подзаголовок
* Пустая строка
* первый буллет без точки
* второй буллет без точки
* третий буллет без точки
* Пустая строка
* Призыв (если есть) без точки

Буллеты пишешь без пустых строк между ними. В начале каждого буллета ставишь минус пробел.

Пример:

![](images/image1.png)

#### Инструкция

* Переходишь на лендинге коуча.
* Копируешь текст с кнопки, вставляешь в строку Headline.
* Копируешь весь текст первого экрана лендинга (заголовок, подзаголовок, буллеты, призыв), вставляешь в строку Text.
* Форматируешь его по правилам форматирования Text.
* Call to action - Learn More.
* Перематываешь до конца страницы, нажимаешь Confirm.
* Дальше Continue.

Платёжные данные
----------------

Выбираешь вариант Payment Method from Business Manager

И отправляешь на модерацию зелёной кнопкой.

Всё, с разделами ты закончил. Но нужно сделать еще пару правок.

Отключи кампанию
----------------

Сразу после создания кампанию надо остановить. Её запустит менеджер проекта после проверки.

Установи лимит кампании
-----------------------

Лимит кампании указан в задании.

#### Инструкция

* Находишь свою кампанию в общем списке кампаний (она самая верхняя)
* Нажимаешь Edit
* В Campaign Spending Limit вводишь лимит кампании
* Дальше Review Draft Items/Continue

Укажи утм метки
---------------

В каждом объявлении должна быть своя утм метка.

Утм метки отличаются названием аудитории, номерами текста, картинок.

#### Инструкция

* Открываешь кампанию, открываешь серию объявлений (biz1 W - 25+)
* Нажимаешь на первом объявлении Edit
* Находишь Website URL
* Ставишь номер картинки, которая используется в этом объявлении (он в названии) Если image 2, то в конце утм метки будет pic2
* Делаешь по аналогии с остальными объявлениями
* В конце нажимаешь Review Draft Items

Если у тебя разные тексты, не забудь указать в утм метке ad1, ad2 и т.д.

Пример

[http://elvirahellmann.icoach.io/?utm\_source=fb-ad&utm\_campaign=28nov&utm\_content=biz\_ad1_pic1](https://www.google.com/url?q=http://elvirahellmann.icoach.io/?utm_source%3Dfb-ad%26utm_campaign%3D28nov%26utm_content%3Dset1ad1pic1&sa=D&ust=1518769283488000&usg=AFQjCNFeGcb7-A2iRnpO_fnau1KgpNwQjg)  \- аудитория бизнесмены, первый текст объявления, первая картинка

[http://elvirahellmann.icoach.io/?utm\_source=fb-ad&utm\_campaign=28nov&utm\_content=neg\_ad1_pic4](https://www.google.com/url?q=http://elvirahellmann.icoach.io/?utm_source%3Dfb-ad%26utm_campaign%3D28nov%26utm_content%3Dneg_ad1_pic4&sa=D&ust=1518769283488000&usg=AFQjCNFDBv3OA0ClTWjf0pBEfyXkjRTNxQ)  \- аудитория переговорщики, первый текст объявления, картинка четвертая

Добавь объявление с видео
-------------------------

Видео \- на ленде коуча.

Название видео Title - название видео на ютубе.

Ad Name пишется по формуле:

* название аудитории
* подчёркивание
* название текста
* подчёркивание
* название видео

Пример: biz\_ad1\_video1

#### Инструкция

* Открываешь ленд коуча, открываешь его видео с ленда в ютубе.
* Добавляешь в адресной строке видео ss перед словом youtube, чтобы выглядело вот так [https://www.ssyoutube.com/watch?v=q2uDU779gPY](https://www.google.com/url?q=https://www.ssyoutube.com/watch?v%3Dq2uDU779gPY&sa=D&ust=1518769283489000&usg=AFQjCNF830F1iX9ZZo-kfaPZsvdpQrJYqg)
* Нажимаешь Enter.
* Нажимаешь Download. Как только видео начало загружаться, загрузку отменяешь.
* Заходишь в загрузки браузера, копируешь ссылку видео, которое ты только что хотел скачать. Например [http://sf-helper.net/download/file.php?id=op&f=&country=in&ts=1512224862&s=bb8b8aec9cfcce9422e257bbc7dd97e2a96eec50&cid=0131f7b6-211b-48ae-9663-01a8c35901f6&uid=edb879305ae7ab87&vid=392&video_id=q2uDU779gPY](https://www.google.com/url?q=http://sf-helper.net/download/file.php?id%3Dop%26f%3D%26country%3Din%26ts%3D1512224862%26s%3Dbb8b8aec9cfcce9422e257bbc7dd97e2a96eec50%26cid%3D0131f7b6-211b-48ae-9663-01a8c35901f6%26uid%3Dedb879305ae7ab87%26vid%3D392%26video_id%3Dq2uDU779gPY&sa=D&ust=1518769283490000&usg=AFQjCNEC0Q9gZ_R3Jkp8rseMDGt-FZBYmA)
* Возвращаешься в Power Editor.
* Дублируешь одно объявление (кнопка Duplicate под названием объявления).
* Открывается окно, опять Duplicate.
* В дублированном объявлении указываешь Ad Name по формуле.
* Меж#1076;у Image и Video/Slideshow выбираешь Video/Slideshow.
* Дальше Select Video, выбираешь раздел Paste a Link.
* В строку Video URL вставляешь ту самую ссылку видео коуча из загрузок хрома.
* В строку Title пишешь название видео как в ютубе.
* Нажимаешь ОК, дожидаешься, пока видео загрузиться.
* Переходишь в Browse Library, выбираешь это видео, нажимаешь Select.
* В строке Website URL - утм метка, в её конце меняешь pic1 на video1.
* Нажимаешь Review Draft Items.
* Выделяешь галочкой это объявление, жмешь Confirm.

Ты можешь и другим способом загрузить видео в объявление, если хочешь.

Добавь ещё две ЦА
-----------------

Минимум три разные аудитории в одной кампании коуча.

#### Инструкция

* Открываешь вкладку Ad Sets.
* Дублируешь только что созданную категорию объявлений.
* Меняешь название аудитории, ее параметры.
* В названии каждого объявления меняешь название аудитории. В  утм метке тоже.
* Пример названия neg - W - 25+ (neg - переговорщики). Утм метка будет кончаться на neg_ad1_pic1 (а было biz).
* Повторяешь эти действия с третьей аудиторией.
* Говоришь Project Менеджеру, что реклама настроена и на рассмотрении.

Чеклист приёмки для менеджера проекта
=====================================

### Название, лимит и активность РК

\[\] Название РК должно быть написано по формуле в графе Campaign Name:

* Conversions
* дата латиницей без пробела

Пример: Conversions 28nov

\[\] РК должна быть неактивна

* В столбце Delivery должно быть Inactive
* Если написано not approved, работу не принимаешь

\[\] Объявления должны пройти модерацию

* В столбце Delivery у каждого объявления и Ad Set должно быть Not Delivering
* Если написано Not Approved или Pending Review, работу не принимаешь

\[\] Лимит кампании должен совпадать с лимитом, указанным в задании

* Находишь свою кампанию

* Нажимаешь Edit
* В Графе Campaign Spending Limit смотришь лимит

### Аудитория

\[\] Настроено три разных аудитории

* Открываешь РК
* Внутри видишь три разные Ad Seta (отличаются названиями)

\[\] Ad Set Name должно быть по формуле:

* Короткое значимое до 10 букв название аудитории латиницей
* Регион
* Возраст

            Пример: biz W - 25+

\[\] Lifetime Budget - 2000 rub

\[\] Schedule – 5 дней

\[\] Location, gender, language, age, Detailed Targeting должны соответствовать концепции

\[\] Стоит галочка в Expand interests when it may increase conversions at a lower cost per conversion

\[\] Optimization for Ad Delivery - Conversions

\[\] Conversion window - AFTER CLICKING AD - 1 day click

* Открываешь РК, видишь Ad Set (bis W - 25+)

* Нажимаешь Edit

* Сравниваешь параметры по чеклисту

### Объявления

 \[\] Названия объявлений Ad Name должно быть по формуле

* название аудитории
* подчёркивание
* название текста
* подчёркивание
* название картинки

Пример: bis\_ad2\_pic3

\[\] Текст совпадает с текстом на первом экране лендинга коуча

\[\] Текст отвечает требованиям форматирования

* Заголовок без точки
* Пустая строка
* Подзаголовок
* Пустая строка
* первый буллет без точки
* второй буллет без точки
* Пустая строка
* Призыв (если есть) без точки

Буллеты \- без пустых строк между ними. В начале каждого буллета ставишь минус пробел.

\[\] Headline - текст на кнопке на лендинге коуча

\[\] В каждом объявлении утм метка написана по формуле

* адрес сайта автора
* «?utm_source=fb-ad»
* «&utm_campaign=» \+ сегодняшняя дата (она же в дате РК)
* «&utm_content=» \+ название объявления (biz\_ad1\_pic1)

Пример Website Url: [http://elvirahellmann.icoach.io/?utm\_source=fb-ad&utm\_campaign=28nov&utm_content=bisad1pic1](https://www.google.com/url?q=http://elvirahellmann.icoach.io/?utm_source%3Dfb-ad%26utm_campaign%3D28nov%26utm_content%3Dset1ad1pic1&sa=D&ust=1518769283495000&usg=AFQjCNFWTr6QB5k-HHkBV3vWZ-qriLr5KQ)

\[\] В утм метке должен стоять соответствующий номер аудитории, текста и картинки

* Выделяешь все Ad Setы одной РК
* Нажимаешь кнопку Create&Edit in a Spreadsheet, выбираешь Export Selected
* Скачивается Excel таблица с данными об объявления, открываешь её
* Если таблица не открывается, загружаешь ее в Google Drive, и открываешь там
* Посередине  меню тыкнул Open with Google Sheets.
* В столбце Link проверяешь утм метку каждого объявления по формуле и номерам картинок и текста
* Проверяешь название объявлений в столбце Ad Name
* Проверяешь Headline в столбце Title
* Проверяешь текст и его формат в столбце Body

\[\] В Графе Identity должна быть группа коуча FB

* Открываешь список кампаний, открываешь свою
* Выделяешь все Ad Setы
* Переходишь в графу Ads

* Открываешь Ad Set (biz W - 25+)
* Выделяешь все объявления галочкой
* Нажимаешь Edit
* В строке Facebook Page - группа коуча FB совпадает с группой FB в задании

            \[\] Call to action - Learn More.

\[\] Количество картинок совпадает с количеством баннером в папке «Креатив»