---
title: Настройка чатбота фейсбук для сбора телефонов
category: Настройка рекламы
order: 4
---

В настройках чатбота мы называем блок с вводом телефона «rec» и для названия линка тоже прописываем значение rec. 

![](/images/ads/chatbot/1.png)

Блок User Input спрашивает телефон и записывает его в атрибут **phone**

![](/images/ads/chatbot/2.png)

В атрибут trello-list-id записываем номер списка trello, в который будут падать заявки.

В атрибут offer записываем, на какой продукт оставлена заявка.

![](/images/ads/chatbot/3.png)

Блок JSON API передаёт данные заявки на наш сервер.

TYPE **POST**  
URL **http://bot.nickvorobiov.com/chatfuel/chatfuel-order.php?fb_id={% raw %}{{messenger user id}}{% endraw %}**  
USER ATTRIBUTES {% raw %}{{offer}} {{trello-list-id}} {{first name}} {{last name}}{{phone}}{% endraw %}

Помимо **phone** можно передать другие атрибуты, если их предварительно спросить у пользователя.

![](/images/ads/chatbot/5.png)

Благодарим за заявку и приглашаем вступить в группу или совершить любое другое полезное действие, например посмотреть видео.

![](/images/ads/chatbot/6.png)
