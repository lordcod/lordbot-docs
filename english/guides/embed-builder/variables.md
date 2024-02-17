---
description: Possible types of variables and where they can be useful
---

# 📑 Variables

## Where do the variables meet?

`settings` -> `Welcomer`

## Guild

| Variable                             | Description                                                            |
| ------------------------------------ | ---------------------------------------------------------------------- |
| `{ guild.id }`                       | Server ID                                                              |
| `{ guild.name }`                     | Name of the server                                                     |
| `{ guild.icon }`                     | Server icon(link)                                                      |
| `{ guild.memberCount }`              | Total number of server participants                                    |
| `{ guild.createdAt }`                | The time when this guild was created                                   |
| `{ guild.premiumSubscriptionCount }` | The number of boosts for this server                                   |

## Member

| Variable                   | Description                                                            |
| -------------------------- | ---------------------------------------------------------------------- |
| `{ member.id }`            | Participant ID                                                         |
| `{ member.mention }`       | Mention of the participant                                             |
| `{ member.username }`      | Name of the participant                                                |
| `{ member.displayName }`   | The display name on the server (if not, then its global name is taken) |
| `{ member.discriminator }` | The participant's discriminator                                        |
| `{ member.tag }`           | The full name of the participant in the format: `LordCode#0745`        |
| `{ member.avatar }`        | Participant's avatar(link)                                             |
