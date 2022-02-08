---
description: Configuration for moderation
---

# Moderation

{% hint style="info" %}
**Tip:** The default prefix for the bot is:`.`
{% endhint %}

**General**

| Command                             | Description                                                                                                                                                                                       |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `set-mute-role`                     | sets the muted role, and applies to a user who gets muted                                                                                                                                         |
| `mute [user] \| [reason/optional]`  | mutes a mentioned user and given a "muted" role                                                                                                                                                   |
| `unmute [user]`                     | unmutes a mentioned user and removes the "muted" role                                                                                                                                             |
| `ban [user ID]/ [reason/optional]`  | <p>bans any user with a reason from a guild server </p><p>ex: [prefix]ban <code>@someone</code> dm advertising</p><p>u must put the / at the end of the user ids in order for the ban to work</p> |
| `unban [userid]`                    | unbans any user from a guild server                                                                                                                                                               |
| `kick [user] \| [reason]`           | kicks a mentioned user with a reason from the guild                                                                                                                                               |
| `warn [user] \| [reason]`           | warns a mentioned user with a reason from the guild server                                                                                                                                        |
| `Resetwarns [user] \| [# of warns]` | resets the mentioned users warns from the guild server the user is in                                                                                                                             |
| `Checkwarns [user]`                 | checks a mentioned users # of warnings                                                                                                                                                            |
| `nick [user] \| [ name]`            | changes a mentioned user with a new nickname                                                                                                                                                      |
| `counselboard`                      | shows a list of warnings from a guild server                                                                                                                                                      |
| `purge [# of message]`              | purges # of messages mentioned e.g. `purge 5`                                                                                                                                                     |
| `steal [emoji]`                     | steals a emoji from any server \[the bot must be in that server in order to steal emoji from that server you are mutual with]                                                                     |
| `createchannel`                     | <p>creates a new existing channel under a category </p><p>e.g. <code>createchannel &#x3C;name> &#x3C;text/voice> &#x3C;category id></code></p>                                                    |
| `editchannel [name]`                | <p>renames a channel [you must be in the channel to rename it]</p><p>e.g. <code>editchannel &#x3C;new name></code></p>                                                                            |
| `removechannel`                     | <p>removes a channel from the category [deletes]</p><p>e.g. <code>removechannel &#x3C;#channel></code></p>                                                                                        |
| `a-role`                            | <p>Gives a mentioned user a role </p><p>e.g. <code>a-role @user &#x3C;role id></code></p>                                                                                                         |
| `r-role`                            | <p>Takes the mentioned user role </p><p>e.g. <code>r-role @user &#x3C;role id></code></p>                                                                                                         |
| `createrole`                        | <p>Creates a new role with the given name</p><p>e.g. <code>createrole owner #ffffff</code></p><p><code>createrole &#x3C;name> &#x3C;color></code></p>                                             |

**Auto Moderation**

| Command         | Description                                                                                           |
| --------------- | ----------------------------------------------------------------------------------------------------- |
| `antilinks on`  | enables anti links disabling users from sending invites from the guild                                |
| `antilinks off` | disables anti links disabling users from sending invites from the guild                               |
| `antiping on`   | <p>enables anti ping role like @everyone or @here role</p><p>preventing users to raid in such way</p> |
| `antiping off`  | <p>disables anti ping role like @everyone or @here role<br>letting users able to ping it.</p>         |

{% hint style="info" %}
**Tip**: when the anti links has been enabled users/admins/mods anyone won't be able to send any type of links like discord invites, youtube links, image links, etc.&#x20;
{% endhint %}
