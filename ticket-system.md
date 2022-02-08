---
description: Configuration for ticket system
---

# Ticket System

{% hint style="info" %}
**Tip:** The default prefix for the bot is:`.`
{% endhint %}

**General**&#x20;

| Command                      | Description                                                                                                          |
| ---------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| `setticketlog [#channel]`    | when someone executes the close ticket command it will send the ticket transcript to the channel it has been set to  |
| `new [reason \| optional]`   | creates a new ticket with or without a reason                                                                        |
| `close [reason \| optional]` | closed (deletes) the ticket with or without a reason                                                                 |
| `rename [name]`              | renames a ticket \[you must be in the ticket to rename it]                                                           |

**When someone created a new ticket everyone can see and send message how can I disable that to only the person who triggers it to read and send messages in the ticket channel?**\
****\
**step 1:**\
`setticketlog [#channel]` you first set the ticket log where you want the tickets to log after when they are closed\
**step 2:**\
`new [reason | optional]` when you trigger this command it creates a new category with the name “Opened Tickets” Do not change the category name for it.\
**Step 3:** \
To **disable everyone** from reading messages and send msg in the ticket channel please click [here](https://cdn.discordapp.com/attachments/756287218846531654/778323907459022888/image0.png) to see how to fix the problem. \
**Step 4:** \
run `new [reason | optional]` again.&#x20;

{% hint style="info" %}
Discord will automatically sync its category permissions when new channels are created, with the channels if discord does not sync its perms you must go to the channel settings press "sync perms" to sync them manually.
{% endhint %}

{% hint style="info" %}
**Tip:** click [here ](https://kbot.gitbook.io/kbot-documentation/guide/ticketing-help)for an easy and full explanation in order to set up the ticketing system.
{% endhint %}
