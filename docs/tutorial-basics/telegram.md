---
sidebar_position: 1
---

# Telegram

## Connect Command

To connect to your Telegram account you should type the next command in the Command Prompt, Powershell, Terminal, or any other integrated terminal you have.

```bash
botito  telegram  connect
```

After typing this command, botito will ask you to type your API ID, API HASH and phone number.

If success botito will save this information so you don't have to type it again.

## Telegram watch list

You should indicate which groups or channels you want the bot to listen to because by default the bot doesn't read all the chats.

First you should get the Chat Id, there are others bot that allow you to do this.

To add a new chat id (Channel, Group) you should type the next command in the Command Prompt, Powershell, Terminal, or any other integrated terminal you have.

```
botito  telegram  set  --chatid=GROUP_ID
```

If success botito will save this information so you don't have to type it again.

To see all the chat ids you have added you can use the next command:

```
botito  telegram  list
```

To remove all the chat ids you have added you can use the next command:
