---
description: Возможные типы переменных и где они могут быть полезны
---

# 📑 Переменные

## Где встречаются переменные?

`settings` -> `Уведомления`

`settings` -> `Тикеты` -> `Сообщения`

## Guild&#x20;

<table><thead><tr><th width="402">Переменная</th><th>Описание</th></tr></thead><tbody><tr><td><code>{ guild.id }</code></td><td>Идентификатор сервера</td></tr><tr><td><code>{ guild.name }</code></td><td>Название сервера</td></tr><tr><td><code>{ guild.icon }</code></td><td>Иконка сервера(ссылка)</td></tr><tr><td><code>{ guild.memberCount }</code></td><td>Общее количество участников сервера</td></tr><tr><td><code>{ guild.createdAt }</code></td><td>Время, когда эта гильдия была создана</td></tr><tr><td><code>{ guild.premiumSubscriptionCount }</code></td><td>Количество бустов для этого сервера</td></tr></tbody></table>

## Member

<table><thead><tr><th width="324">Переменная</th><th>Описание</th></tr></thead><tbody><tr><td><code>{ member.id }</code></td><td>Идентификатор участника</td></tr><tr><td><code>{ member.mention }</code></td><td>Упоминание участника</td></tr><tr><td><code>{ member.username }</code></td><td>Имя участника</td></tr><tr><td><code>{ member.displayName }</code></td><td>Отображаемое имя на сервере (если объект не определён, используется его глобальное имя)</td></tr><tr><td><code>{ member.discriminator }</code></td><td>Дискриминатор участника</td></tr><tr><td><code>{ member.tag }</code></td><td>Полное имя участника в формате: <code>LordCode#0745</code>, <code>lordcode</code></td></tr><tr><td><code>{ member.avatar }</code></td><td>Аватар участника (ссылка)</td></tr></tbody></table>

## Stream

<table><thead><tr><th width="316">Переменная</th><th>Описание</th></tr></thead><tbody><tr><td><code>{ stream.username }</code></td><td>Имя пользователя</td></tr><tr><td><code>{ stream.title }</code></td><td>Название стрима</td></tr><tr><td><code>{ stream.gameName }</code></td><td>Название игры</td></tr><tr><td><code>{ stream.thumbnailUrl }</code></td><td>Изображения кадра за последние 5 минут трансляции</td></tr><tr><td><code>{ stream.avatarUrl }</code></td><td>Аватар пользователя (ссылка)</td></tr><tr><td><code>{ stream.url }</code></td><td>Ссылка на стрим</td></tr></tbody></table>

## Video&#x20;

| Переменная              | Описание              |
| ----------------------- | --------------------- |
| `{ video.username }`    | Имя пользователя      |
| `{ video.title }`       | Название видео        |
| `{ video.description }` | Описание видео        |
| `{ video.url }`         | Ссылка на видео       |
| `{ video.videoIcon }`   | Иконка видео (ссылка) |

## Bot

Имеет все те же параметры что и [#member](variables.md#member "mention") только начиная с `bot.`

