---
icon: user-police
---

# Политика конфиденциальности

> Этот документ содержит политику конфиденциальности и соглашение, которые вы принимаете, добавляя бота на сервер или становясь участником такого сервера.&#x20;

{% embed url="https://support-dev.discord.com/hc/en-us/articles/8562894815383-Discord-Developer-Terms-of-Service" %}
Документ не заменяет Условия обслуживания разработчиков.
{% endembed %}

## Боты, услуги и серверы

Ниже приведен список ботов, к которым применяется эта политика конфиденциальности:

{% embed url="https://discord.com/oauth2/authorize?client_id=1095713975532007434" %}
[LordCord](https://discord.com/oauth2/authorize?client_id=1095713975532007434)
{% endembed %}

Эта политика конфиденциальности также применяется ко всем этим сайтам и их поддоменам:

{% embed url="https://lordcord.xyz" %}
[lordcord.xyz](https://lordcord.xyz)
{% endembed %}

## Терминология

* **Менеджер сервера** - любой, кто имеет возможность добавить бота на сервер или настроить бота для сервера. Обычно это администратор или модератор.
* **Участник сервера** - любой, кто является участником сервера, на который добавлен один из ботов.
* **Пользователь услуги** - любой, кто авторизует приложение для области, предоставляющей дополнительную информацию.
* **Интент** - специальные права, выданные Discord для получения уникальных данных.

## Собираемые данные

* Конфигурации сервера
* Архивы сообщений
* Данные и контент для автоматических задач
* Сохраненные ссылки, URL или текст
* Список ролей участников
* Данные аватаров
* Идентификаторы пользователей
* Предыдущие имена пользователей
* Дата и время последнего действия
* Любые данные, необходимые для стандартной работы ботов Discord, такие как разрешения на сервере

## Данные, собираемые через авторизацию

* Имя пользователя
* Discord ID
* Данные аватара

## Права пользователей

{% hint style="warning" %}
Вы можете отказаться от отслеживания любых событий бота, включая привилегированные интенты. В случае отказа от интентов, могут возникнуть проблемы, например, если вы отказываетесь от интента участников сервера, то бот не сможет отслеживать вас при входе на сервер и вы не сможете получить автоматическую роль.
{% endhint %}

## Интент присутствия

{% hint style="info" %}
Бот сможет отслеживать вашу активность.

Это необходимо для экономики, логов, а также некоторых команд.

Владелец сервера может запросить отказ от этого интента.
{% endhint %}

## Интент контента участников

{% hint style="info" %}
Бот сможет отслеживать ваши сообщения, их содержание, файлы и вложения.

Это необходимо для логов, модерации, архивирования заявок, а также для нашей нейронной сети.

Мы не храним ваши сообщения за пределами Discord, только если пользователь не написал в заявку и менеджер сервера включил архивирование сообщений.

Для нейронной сети мы используем следующие библиотеки: TensorFlow, NLTK, Gensim.

У нас есть 2 нейронные сети:

* Распознавание вопросов.
* Поиск похожих вопросов, которые записали менеджеры.
{% endhint %}

{% hint style="success" %}
Мы используем сообщения сообщества, содержащие вопросительный знак, для обработки нашей нейронной сети. Перед обработкой ботом менеджер должен подтвердить, что это действительно вопрос.

Что касается безопасности и чтения контента, мы сканируем только каналы, которые **открыты для всех**, и при условии, что **все могут находиться на этом сервере**, т.е. @everyone будет разрешено createInvite=True.
{% endhint %}

{% hint style="warning" %}
Пользователь может отказаться от использования этого интента.

Владелец сервера может отказаться от обучения нейронной сети на своем сервере.
{% endhint %}

## Хранение данных

{% hint style="info" %}
Все сохраненные данные хранятся на **защищенных серверах**.

Методы хранения различаются, большинство данных хранится в защищенных паролем базах данных, таких как **PostgreSQL** или **MongoDB**.
{% endhint %}

{% hint style="warning" %}
Имейте в виду, что даже при такой защите, данные не могут быть на 100% защищены.
{% endhint %}

{% hint style="success" %}
Прилагаются все усилия для обеспечения безопасности ваших данных, но их абсолютная безопасность не может быть гарантирована.
{% endhint %}

## Обратная связь

{% hint style="success" %}
Мы приветствуем обратную связь **по любым вопросам и услугам** без исключения.
{% endhint %}

**Пожалуйста, в первую очередь обращайтесь через тикеты на сервере поддержки.**

Электронная почта: `support@lordcord.xyz`\
Контакты разработчиков:&#x20;

* Менеджер, дискорд - [@dybfuo](https://discord.com/channels/@me/1134188341231890543), телеграмм - [@dybfuo](https://t.me/dybfuo)
* Разработчик, дискорд - [@lordcode](https://discord.com/channels/@me/1134188341231890543), телеграмм - [@lord\_cord](https://t.me/lord_cord)

{% embed url="https://lordcord.xyz/support" %}
Сервер поддержки
{% endembed %}

## Соглашение

{% hint style="info" %}
_Добавляя бота на ваш сервер_ или используя этих ботов или услуги любым образом, вы соглашаетесь с политикой, изложенной в этом документе.

Кроме того, вы как менеджер сервера соглашаетесь информировать своих пользователей об условиях обслуживания, предоставленных разработчиком, и содержании этого документа.
{% endhint %}

{% hint style="danger" %}
Если вы, менеджер сервера, не согласны с этим документом, **вы можете удалить бота(ов)** с сервера.

Если вы, пользователь сервера, не согласны с этим документом, **вы можете покинуть сервер**, на котором находятся боты.

Если вы, пользователь услуги, не согласны с этим документом, **вы можете отменить авторизацию приложения(ий)** в меню "Авторизованные приложения".
{% endhint %}

