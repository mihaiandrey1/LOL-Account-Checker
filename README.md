# LoL Account Checker

***Thanks for checking out my repository! If you think it's helpful, please consider giving it a star.***

This program is a League of Legends account checker supporting multi threading with multiple features including the ability to run checks on multiple accounts, export all account information to a folder, and display comprehensive details about each account, including purchase dates and more.

# This file is to large to put here so download link is here
dw: https://drive.google.com/file/d/1_XPoqupnwgA1QFSVn_ASYvivgrRf6gUx/view?usp=drive_link
virus total: https://www.virustotal.com/gui/file/9317ce14b48817e2e3b8e655ae4bd3fbb2ac5a806f6408b5bfaa3747b6f3e921?nocache=1

*Please be aware that this program is not 100% stable and can rarely catch unknown exceptions.*

## Core Features

- Multi-threading
- Run checks on multiple accounts (from text file)  
- Exports all accounts information to folder  
- Comprehensive details on each successfully checked account, including purchase dates, owned champions, owned skins, and more.  
- Automatically execute Hextech Loot related tasks such as disenchanting, claiming etc.
- Automatic removal of all friends and friend requests.
- Claim event rewards
- Re-queue system for accounts that failed due to errors.

## How to use

*Note: I recommend using at most 8 threads.*  
*Note: Rarely, accounts can show as login failed when they are active.*

### First Way

The first way to run the application is by downloading the source code and running it in a coding environment like visual studio.

### Second Way

*Only works on Windows operating systems.*

The other way which is easier is to download the **Account Checker Release** found in the root folder of the directory. There will always be two zipped files of the program, the newest version, and the previous version. Running the exe file should run the application.

Alternatively, you can download the latest release.

## How it works
The program creates a Riot client to authenticate the user and a League client to execute authorized requests. It then performs a series of requests to gather account-related data and perform tasks.
