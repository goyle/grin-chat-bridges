# grin-chat-bridges

## Installing Matterbridge
To get started, install the latest stable release of matterbridge: https://github.com/42wim/matterbridge/releases/latest
\
You may need to make the binary executable if you are using Linux.

Create a configuration file for each gateway: https://github.com/42wim/matterbridge/wiki/How-to-create-your-config


## Creating a Discord bot
Setup a Discord bot by following the instructions here: https://github.com/42wim/matterbridge/wiki/Discord-bot-setup
\
You will need to invite the bot to the Discord server and add the **bot token** to the matterbridge configuration file.


## Creating a Telegram bot
Setup your Telegram bot by following the instructions here: https://core.telegram.org/bots#6-botfather
\
You will need to invite the bot to the Telegram group and add the **API token** to the matterbridge configuration file.

Be sure to adjust the privacy settings for your bot to view messages from the channel in the matterbridge output.
Using BotFather, change the `/setprivacy` setting to `Disable`. See here: https://github.com/42wim/matterbridge/wiki/Section-Telegram-%28basic%29#generate-events--output

You will need to insert the **Telegram group chat ID** in the config file. You can find the ID in one of two ways:

1. https://github.com/42wim/matterbridge/wiki/Section-Telegram-%28basic%29#via-chatid
2. https://www.linkedin.com/pulse/telegram-bots-beginners-marco-frau

## Creating a Keybase bot
Create a new dedicated Keybase account specifically for the bot. The account needs to be logged in on the system you are running the bridge on.

See here: https://github.com/42wim/matterbridge/wiki/Section-Keybase-%28basic%29

