# DiscordDialogueParser
bot to parse dialogues from discord

## Description

Script to parse conversations from discord chats for machine learning applications

## Instalation

Run in cmd:

    pip install -r requirements.txt

## Usage

Get your discord token and chat_id.

The first is obtained by entering Discord via browser and following these instructions 
F12 -> Network -> F5 (wait for reboot) -> science -> Headers -> authorization, copy this value.

The second is by going with the browser to the needed chat and copying the last set of digits in the URL.

The number of threads represents the number of parallel operations (the more the faster).

Num of messages to find is the number of end messages that would be parsed in the begging.
