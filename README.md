***
To create a bot, we need to give it a name, address and get a token - a string that will uniquely identify our bot for Telegram servers. Let's go to Telegram under our account and open the "father of all bots", BotFather.

We press the "Run" button (or send / start), in response BotFather will send us a list of available commands:

/newbot - create a new bot; /mybots - edit your bots; / setname - change the name of the bot; /setdescription - change the description of the bot; /setabouttext - change information about the bot; /setuserpic - change the bot's avatar photo; /setcommands - change the list of bot commands; /deletebot - delete the bot. Let's send the /newbot command to the bot bot to create a new bot. In response, he will ask you to enter the name of the future bot, you can write it in Russian. After entering the name, you will need to send the address of the bot, and it must end with the word bot. For example, xakepbot or xakep_bot. If the address is already taken by someone, BotFather will begin to apologize and ask you to come up with something else.

When we finally find a free and beautiful address for our bot, we will receive a message in response, in which, after the phrase Use this token to access the HTTP API, a string of letters and numbers will be written - this is the token we need. Let's save it somewhere on our computer so that we can later use it in the bot script.

There are several ready-made modules for interacting with the Telegram API. The simplest of them is Telebot. To install it, type

pip install pytelegrambotapi On Linux, it may be necessary to write pip3 instead of pip to indicate that we want to work with the third version of Python.
***
