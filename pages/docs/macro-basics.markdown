---
layout: page
title: Macro Basics
permalink: /docs/macro-basics
nav_order: 2
---

<details markdown="block">
<summary>Table of Contents</summary>

> * [**PC Settings**](#pc-settings)
> * [**Installation and Usage Guide**](#installation-and-usage-guide)
>   * [Get Bot Link](#get-bot-link)

</details>

# PC Settings

1. Display Settings

    ☙ Any settings that impact your PC display will need to be setup properly as macro reply solely on image detection.

    **Windows Display**

    ☙ Right click on your Desktop → Display Settings

    ✧ Night light: Off
    
    ✧ Use HDR: Off

    ✧ Scale: 100%

    ✧ Display Resolution: Any resolution upto 3k

    ✧ Display Orientation: Landscape
    
    ![](../../assets/gifs/Display_Settings.gif)

2. Power Options

    ☙ Apply the following settings to prevent your PC screen from sleeping after macroing for a while:

    ✧ Open the Power & Sleep settings on your PC → Set the 'Screen' or 'Display' sleep timer to 'Never' to prevent the screen from sleeping

    ✧ This will ensure that your PC screen remains awake while the macro is running for an extended period
    
    ![](../../assets/images/Power_and_Sleep.png)
    
3. Graphics Card

    ☙ Some custom graphics card setting can impact how your display look which might cause the macro to not detect certain images. If you did not manually change any of said settings then you can skip to Step 4.

    **AMD**

    ☙ Head to AMD Software: Adrenalin Edition → Gaming → Graphics → Scroll down to Image Sharpening → Turn Off

    ![](../../assets/images/AMD_Image.png)

    **NVIDIA**

    ☙ Head to NVIDIA Control Panel → Manage 3D Settings → Image Scaling → Off

    ![](../../assets/images/NVIDIA_Image.png)

4. Program Interference

    ☙ Please be cautious of any programs you run alongside the macro. You are likely more familiar than I am with the features of your programs, so please be aware if any of them may interfere with or block the macro's usage. An example of this is 'Screen Overlay'

    **Common Overlay Issues**

    ✧ Discord VC/Text Overlay

    ✧ Popup Text Notifications

    ✧ FPS Counter

5. Monitor Settings

    ☙ Macro uses image detection, requiring your monitor to be on. However, if turning off your monitor only shuts off the screen while your PC continues to send images to the display for the macro to detect, then it shouldn't be a problem

    ☙ For those that have issue when monitor is off, try using the HDMI port instead of the display port on your monitor. If this doesn't work, you may need to resort to using Remote Desktop Protocol (RDP) - *Only for ROBLOX*

    **Multiple Monitors (skip this if you have 1 monitor)**

    ☙ In most case, if you just run both the macro and the game on your primary monitor there shouldn't be any issue

    ☙ If above doesn't work, you might have to unplug your 2nd monitor

6. Remote Desktop Protocol (skip this if you don't use RDP) - *Only for ROBLOX*

    ☙ Since Roblox don't work with Virtual Machines (VM) anymore, the only alternative is an RDP

    ☙ If you were able to set up RDP, you can just install the macro and use it right away as it uses the same whitelist as your main PC

    ☙ Don't use Ctrl key as your hotkey to tab out of RDP, this will cause RDP to still be holding Ctrl and you will click through items on Roblox which will cause issue for the macro


# Installation and Usage Guide

1. File Types

    ☙ All of my macro will have the following files:
    
    ✧ .exe
    
    ✧ .env (once .exe has been ran once)

    ![](../../assets/images/File_Types.png)

2. Downloads

    ☙ Download the latest macro of any chosen game from:
    
    ✧ [Macro Releases on Github](https://github.com/bayamacro?tab=stars)

    **IMPORTANT**: It's highly recommended you all update to the latest version.

3. Approve Files

    ☙ Macro exe file is an executable file that can simulate your mouse and keyboard so PC think its dangerous, you have to manually approve the file like below.

    ☙ If this doesn't work, you might have to disable your window defender.

    ![](../../assets/images/Error_1.png)

4. Organize Files

    ☙ Once all files are downloaded, drag them all into a specific folder, **DON'T** just leave them in the 'Downloads' Folder.

    ☙ In this folder, you should have the macro executable and 'discord.env' if executable has been ran before.

5. Anti Virus Settings

    ☙ You will have to exclude the macro folder from your anti virus program. Follow exclusion guide below if you don't have any other anti virus program.

    **Windows Defender**

    ✧ Virus & threat protection → Manage settings → Scroll down to 'Exclusions → Add or Remove Exclusion

    ✧ Then browse for the folder where the macro executable is located. (Exclude whole folder, not each file seperately)

    ![](../../assets/gifs/Windows_Security_Exclude_Folder.gif)

6. Start the Macro

    ☙ Finally you can run the macro by double clicking the executable file (the icon on the exe will vary depending on what game the macro is for)

    ☙ Use "[" to start/pause and "]" to stop macro. If the macro doesn't stop after pressing the key, it means there are macro pop up box that you haven't closed, you can find the by pressing **Alt + Tab**

    ☙ You can also press **Ctrl + Alt + Del** and use 'Task Manager' to end task if all else failed

7. Discord Pings

    ☙ My macro will have a 'Discord Ping' Feature that notify you of an event to your own Discord Server

    ☙ To use it, you'll need:
    'Discord User ID' 
    'Discord Webhook URL'

    ☙ To get Discord User ID, go to User Settings → Advanced → Enabled 'Developer Mode' → Press 'ESC' or Close Settings → Click on profile (left of 'User Settings') → Copy User ID

    ![](../../assets/gifs/Discord_User_ID.gif)

    ☙ To get Webhook URL, go to your own server → Edit Channel → Integrations → Webhooks → Copy Webhook URL

    ![](../../assets/gifs/Discord_Webhook_URL.gif)

8. Discord Commands

    ☙ Go to <a href="https://discord.com/developers/applications" target="_blank">Discord Developer Applications</a> → Click 'New Applications' → Input Bot Name & Accept TOS → Click 'Bot' under 'Settings' → Scroll down Enable 'Message Content Intent' and 'Save Changes' → Scroll back up and 'Reset Token' → Copy the 'Token'

    ![](../../assets/gifs/Discord_Set_Bot.gif)

    ☙ Right Click 'discord.env' (If not in the same directory as macro executable, run the exe and close it) and open as 'Notepad' or any code editors → Within the 2 single quotation marks, paste the 'Discord Token'

    ![](../../assets/gifs/Edit_env.gif)

    ☙ Get 'Application ID' - Go to <a href="https://discord.com/developers/applications" target="_blank">Discord Developer Applications</a> → Go to the Application you've created → Under 'Settings' Click 'General Information' → Copy 'Application ID'

    ![](../../assets/gifs/Application_ID.gif)

    ☙ [Get Bot Link](#get-bot-link)

    ☙ Add the 'Bot' to the discord server of your choice.
    
    ![](../../assets/gifs/Add_Bot_To_Server.gif)

    ☙ If you've 'Privated' any channels make sure the bot is able to view the channel / send messages / mention

    ✧ View Channel: On
    
    ✧ Send Messages: On

    ✧ Embed Links: On

    ✧ Attach Files: On

    ✧ Mention @everyone, @here and All Roles: On
    
    ![](../../assets/gifs/Bot_Permissions.gif)

## Get Bot Link

☙ Input the 'Application ID' into the box below.

{% include html/get-bot-link.html %}