# Discord bot template
This is a template for creating a Discord bot in [Python](https://www.python.org/)

# How to use this template

## Download the template
1. Click on [Use this template](https://github.com/Mankifg/DiscordTemplateBotPy/generate)
2. Follow instructions on github
3. Navigate in the desired directory and type: 
```
git clone [your repository link]
cd DiscordTemplateBot
py -m pip install -r requirements.txt
```

## Creating bot at Dev Portal
1. Create a new Discord bot at [Discord dev portal](https://discord.com/developers/applications)
2. Create a bot and under **Privileged Gateway Intents** turn on at least **MESSAGE CONTENT INTENT** (Turn others if necessary)
3. Invite the bot under **OAuth2**-**URL Generator** as bot and pick bot permissions
4. Invite the bot by pasting link in the browser (and logging in) and chosing the **server**

## Code itself
1. Rename **temp.env** to **.env**
2. Found your token at **Bot** - **TOKEN**
3. Paste it into the **.env** file with format: ```TOKEN=[your token]``` 
4. Run the by running the `main.py` file
5. The bot should be online. In case of any errors submit a issue


# Errors / Improvments / Questions
If you have any of above please **submit a Issue** at [Issues](https://github.com/Mankifg/DiscordTemplateBotPy/issues/new)

