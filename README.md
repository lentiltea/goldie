Goldie is a discord bot made for creating random tags using text files, amongst other things. They are written using discord.py, a python extension for Discord.

This file will explain how Goldie works, along with a bit 
---
To create random tags, just upload a text file and use the .t create [tagname] command to create a random tag. Then, whenever you use .t [tagname], the bot will pick a response at random from a line in the text file you uploaded. Remember to put each seperate response on a new line in the text file.
There are three ways to edit tags:
.t edit lets you add one new entry to a tag, by writing the new entry in the message you send. (for example, .t edit [tagname] [content]).
.t add lets you add a text file onto the end of a tag, essentially letting you add multiple entries. Just upload the text file you want to add onto the end with the command .t add [tagname]
.t rewrite lets you overwrite a tag with a new text file. Again, simply upload the textfile and use .t rewrite [tagname]

You can delete tags with .t delete [tagname].

---
Tags have three states of being, private, public, and open. Private tags can be viewed by anyone, but only edited by moderators and the person who made the tag. Public tags can be edited by anyone, but only deleted or rewritten by moderators or the person who made the tag. Open tags can be edited, deleted, and rewritten by anyone.
When you create a tag, it is set to private by default. You can change a tags state of being using .t edit [private/public/open] [tagname].

---
Goldie can also do other things. .steffify lets Goldie send a message with the Steffi_wow emote underneath each letter. Replace the steffi_wow emote with your own custom emote if youd like to change the commands output to have a different emote under each letter!
.emote lets Goldie grab the image link to any custom emote in a server.
.get is a command that lets Goldie grab various useful things. .get avatar causes Goldie to respond with the avatar of the person who used the command. .get servericon causes Goldie to respond with the icon of the server the command is used in. .get channelcount causes Goldie to respond with the number of voice channels, text channels, and categories in the server the command is used in.
.ocprompt is a command inspired by Hap's (bluering's) twitter oc prompt game! Goldie will give you a theme, colour, hair style, weapon / power, and extra detail to use when creating an oc!

---
The file keep_alive contains flask code to run a bot permanently through repl. Please note repl does have hosting issues, and can occasionally be blocked by discord for invalid api requests or spam requests. If you wish for your bot to be more reliable, paid hosting may be the option you have to take to do so. Repl is free, and so has some issues. Alternatively, if you're looking for something cheaper, it may be worthwhile looking into hosting similar to Goldie's, with a private device that runs the code. Raspberry Pis are great for this.

---
Please DM LentilTea#4801 on Discord if you have any queries, issues, or general needs regarding Goldie or this open source variant of the code. Thanks!
