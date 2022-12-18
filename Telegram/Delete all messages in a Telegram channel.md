## Delete all messages in a Telegram channel using a bot with python3

To delete all messages in a Telegram channel using a bot and the channel's ```username```, you can use the following code:

```python
import telebot

# Replace TOKEN with your bot's token
bot = telebot.TeleBot("TOKEN")

# Set the channel username of the channel you want to delete messages from
channel_username = "@examplechannel"

# Fetch the channel object using the username
channel = bot.get_chat(channel_username)

# Fetch all messages in the channel
messages = bot.get_messages(channel.id)

# Delete all messages
for message in messages:
    bot.delete_message(channel.id, message.message_id)
```
This code uses the ```TeleBot``` class from the telebot library to interact with the Telegram API. It first fetches the channel object using the get_chat method and the channel's username, and then uses the id attribute of the channel object to fetch all messages in the channel. Finally, it iterates through the messages and uses the ```delete_message``` method to delete each message.

Note that this code will only work if the bot has the necessary permissions to delete messages in the channel. You may also need to handle pagination if there are a large number of messages in the channel.


