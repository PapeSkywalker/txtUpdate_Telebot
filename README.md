# Telebot to push txt file changes (in python)

## Script concept :writing_hand:

The idea behind this Telegram bot revolves around real-time monitoring and notification of changes in specific text files. This bot has been created to be used in conjunction with a keylogger on the server-side. Upon initiation with the '/start' command, the bot registers the chat ID and begins sending updates to users regarding any modifications in the designated files.

The bot monitors a set of predefined text files containing sensitive information such as credit card details, credentials, emails, IBANs, and passwords. Through a continuous file change checking mechanism implemented in a separate thread, the bot constantly monitors these files for any modifications. Once a change is detected, the bot immediately notifies all registered users by sending a message containing the newly added information from the respective file.

To ensure efficient communication and user engagement, the bot employs emojis and clear categorization in the notification messages, indicating the type of information that has been updated. This not only enhances the readability of the messages but also allows users to quickly identify the nature of the information being conveyed.
<br>

## Notes :closed_lock_with_key: 

📝 First of all ensure to put your Bot Api Key at the start of the script where it's written `API_KEY = "<YOUR_APIKEY>"`

📝 I do not condone or support the use of this software for any malicious or illegal activities, so please be good 😇
