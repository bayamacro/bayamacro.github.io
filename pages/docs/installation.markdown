---
layout: page
title: Installation and Usage Guide
permalink: /docs/installation-and-usage
nav_order: 2
---

<details markdown="block">
<summary>Table of Contents</summary>

> * [**How to Install**](#how-to-Install)
> * [**Enable Discord Commands**](#enable-discord-commands)
>   * [For getting token](#for-getting-token)

</details>

# How to Install

1. File Types

    ☙ All of my macro will have the following files:
    
    ✧ .exe
    
    ✧ .env (once .exe has been ran once)

    <a href="/assets/images/File_Types.png"><img src="/assets/images/File_Types.png" width="500"></a>

2. Downloads

    ☙ Download the latest macro of any chosen game from:
    
    ✧ [Macro Releases on Github](https://github.com/bayamacro?tab=stars)

    **IMPORTANT**: It's highly recommended you all update to the latest version.

3. Approve Files

    ☙ Macro exe file is an executable file that can simulate your mouse and keyboard so PC think its dangerous, you have to manually approve the file like below.

    ☙ If this doesn't work, you might have to disable your window defender.

    <a href="/assets/images/Error_1.png"><img src="/assets/images/Error_1.png" width="500"></a>

4. Organize Files

    ☙ Once all files are downloaded, drag them all into a specific folder, DON'T just leave them in the 'Downloads' Folder.

    ☙ In this folder, you should have the macro executable and 'discord.env' if executable has been ran before.

5. Anti Virus Settings

    ☙ You will have to exclude the macro folder from your anti virus program. Follow exclusion guide below if you don't have any other anti virus program.

    **Windows Defender**

    ✧ Virus & threat protection > Manage settings > Scroll down to 'Exclusions > Add or Remove Exclusion

    ✧ Then browse for the folder where the macro executable is located. (Exclude whole folder, not each file seperately)

    <a href="/assets/gifs/Windows_Security_Exclude_Folder.gif"><img src="/assets/gifs/Windows_Security_Exclude_Folder.gif" width="500"></a>

6. Start the Macro

    ☙ Finally you can run the macro by double clicking the executable file (the icon on the exe will vary depending on what game the macro is for)

    ☙ Use "[" to start/pause and "]" to stop macro. If the macro doesn't stop after pressing the key, it means there are macro pop up box that you haven't closed, you can find the by pressing Alt + Tab.

    ☙ You can also press Ctrl + Alt + Del and use 'Task Manager' to end task if all else failed

7. Discord Pings

    ☙ My macro will have a 'Discord Ping' Feature that notify you of an event to your own Discord Server

    ☙ To use it, you'll need:
    'Discord User ID' 
    'Discord Webhook URL'

    ☙ To get Discord ID, go to User Settings> Advanced> Enabled 'Developer Mode'> Press 'ESC' or Close Settings> Click on profile (left of 'User Settings')> Copy User ID

    <a href="/assets/gifs/Discord_Webhook_ID.gif"><img src="/assets/gifs/Discord_Webhook_ID.gif" width="500"></a>

    ☙ To get Webhook URL, go to your own server> Edit Channel> Integrations> Webhooks> Copy Webhook URL

    <a href="/assets/gifs/Discord_Webhook_URL.gif"><img src="/assets/gifs/Discord_Webhook_URL.gif" width="500"></a>



# Enable Discord Commands

1. To allow discord commands, you must first run the Baya's Macro exe file.

2. Once ran, a file called 'discord.env' should be in the current working directory.

3. Right click and Edit in Notepad.

2. Edit the value discord_Token by editing the values inside the single quotation marks ` `. 

{: .warning }
Do not delete any lines or write stuff in non-designated places.

{: .note }
An Example of how the 'discord.env' file should look: 

```
discord_Token = 'ENTER_TOKEN_HERE'
```
    
## For getting token

WORK IN PROGRESS