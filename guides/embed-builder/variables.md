---
description: Возможные типы переменных и где они могут быть полезны
---

# 📑 Переменные

## Где встречаются переменные?

`settings` -> `Приветствие` -> `Приветственное сообщение`

## Guild

<table><thead><tr><th width="391">Переменная</th><th>Описание</th></tr></thead><tbody><tr><td><code>{ guild.id }</code></td><td>Идентификатор сервера</td></tr><tr><td><code>{ guild.name }</code></td><td>Название сервера</td></tr><tr><td><code>{ guild.icon }</code></td><td>Иконка сервера(ссылка)</td></tr><tr><td><code>{ guild.memberCount }</code></td><td>Общее количество участников сервера</td></tr><tr><td><code>{ guild.createdAt }</code></td><td>Время, когда эта гильдия была создана</td></tr><tr><td><code>{ guild.premiumSubscriptionCount }</code></td><td>Количество бустов для этого сервера</td></tr></tbody></table>

## Member

| Переменная                 | Описание                                                             |
| -------------------------- | -------------------------------------------------------------------- |
| `{ member.id }`            | Идентификатор участника                                              |
| `{ member.mention }`       | Упоминание участника                                                 |
| `{ member.username }`      | Имя участника                                                        |
| `{ member.displayName }`   | Отображаемое имя на сервере(если нету то берется его глобальное имя) |
| `{ member.discriminator }` | Дискриминатор участника                                              |
| `{ member.tag }`           | Полное имя участника в формате: `LordCode#0745`                      |
| `{ member.avatar }`        | Аватар участника(ссылка)                                             |
