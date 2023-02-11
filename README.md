
# Basic Stat Counter
Helloooo! 🦆 I felt like making something useless, so here we areee~
  

## Current Features:

- Message per channel breakdown
- Reset all values to 0.

  

## Installation

Create two new custom commands.

**Collection**

This command needs to detect whenever a user sends a channel on any message.
Set this to type "Regex" and set the Trigger to "\A", and set it to not be case sensitive. This way, all messages are picked up by the command. If you'd like to choose specific channels to include or exclude, or choose to not count messages from specific roles, feel free to use YAGPDB.xyz's inbuilt functionality to do this, in the bottom-right of the page. Press save once you're done!

**Display**

This command is for admins only, to show or reset the stat tracker.
Set the trigger type to "Command (mention/cmd prefix)" and set the trigger to whatever you'd like.  Make sure you use YAGPDB.xyz's inbuilt menus to only allow server admins access to this command.

## Usage
*For the purpose of this README, I'll be using `-` as the bot prefix and `cstats` as the trigger.*
So far, there's not a whole lot to do. The command will start counting right after installation, but I suggest immediately running `-cstats reset` to save the current time.  Use `-cstats show` to show the number of messages sent to each channel, as well as the timestamp for when it was last reset. `-cstats reset` will reset the counter to 0 for all channels.

![Demo of the bot on Discord.](https://i.imgur.com/TAs9Hec.png)