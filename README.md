# SimpleDiscordBot

Step 1:Go to this link : https://discordapp.com/developers/applications

Step 2:Click New Application in the Top Right Corner.

Step 3:Enter the Application Name.

Step 4:In General Information section under the Application Name there will be Client ID (COPY IT in Notepad)

Step 5:In Bot Section there will be an option called Add Bot just click it and Name your Bot.

Step 6:In Bot Section Under the Username there will be Token (COPY IT in Notepad).

Step 7:In Bot Section Scroll there will section called BOT PERMISSIONS. Under BOT PERMISSIONS make a Tick in Send Messages, Send TTS Messages and Read Message History.

Step 8:After Ticked under that there will be a Permission ID (COPY IT in NOTEPAD)

#INTEGRATING WITH DISCORD SERVER

Step 1:The above copied Client ID and PermissionID is pasted in the curly braces area in the link and remove the bracecs after copied Link : https://discordapp.com/oauth2/authorize?client_id={CLIENTID}&scope=bot&permissions={PERMISSIONINT}

Step 2:Create an Discord Server in Discord APP.

Step 3:After pasted in the above link, copy the link and paste it in your browser and search.It directs you to the Discord Website which asks for authorization, verify it and it ask your Server Name which you where created in Discord APP ,Select the Server name from the drop down menu.

Step 4:Bot is Integrated, now go to the Discord Server which you created and select the Setting button and click Permissions there will be a section called ROLES/MEMBERS click the + icon and search for bot you created.

Step 5:And in the setting section click Permissions and scroll down Text Permissions and tick Send Messages, Send TTS Messages and Read Message History.

Step 6:Integration is complete

#Run Progam

Step 1:Do you remember we copied the Token.Create a token.txt file and paste the token

Step 2:py -3 -m pip install -U discord.py [It is used to install Discord Python Package]

Step 3:Run the DiscordBot.py
