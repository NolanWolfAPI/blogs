## What is Modmail?
Modmail is an open source bot created by Kyb3r on github!
Modmail is used for staff and users too communicate through a bot dm!

Modmail is hosted on heroku, but heroku only gives you 500 hours.
In this tutorial I'll teach you how to self-host it!

## STEP 1: Download the zip of modmail!
You can download it [here!](https://github.com/kyb3r/modmail/archive/master.zip)

## STEP 2: Install Python 3.7.3
You can install it by clicking here [link]( https://www.python.org/downloads) 

## STEP 3: Update the values!
Open the file and click on `.env.example` and open it with your favorite text editor and put your values!
``TOKEN= your bot’s token.
LOG_URL= the URL of your log viewer Heroku app (ie. https://yourlogviewerappname.herokuapp.com).
GUILD_ID= the ID of the server your bot operates in.
OWNERS= your user ID (ie. OWNERS=9821302031291298, or if multiple owners, OWNERS=9821302031291298,9781239213813229,924822913921391).
MONGO_URI= your Mongo connection URI from the MongoDB setup.
from https://taaku18.github.io/modmail/local-hosting/``` After you're done, make sure to save the file as `.env`!

## STEP 4: Open your command prompt and relocate your file!
You can this by going to your files and going to the modmail file, and pressing right click + shift at the same time, and clicking, 
`open command prompt`! If you're on linux or mac, open your terminal and type this command ```cd path/to/desktop/modmail-master```!

## STEP 5: Installing the requirements!
Install the requirements.

MacOS or Linux users, type in the following:
```pip3.7 install pipenv && pipenv install```
Windows users, type in the following:
```py -3.7 -m pip install pipenv && py -3.7 -m pipenv install```

## STEP 6: Installing discord!
No, I do not mean downloading discord,
you can do this by typing ```py -3.7 -m pipenv install discord```

## STEP 7:Running the bot!
For this part you'll need to run ```py -3.7 -m pipenv run python bot.py```
Check and see if your bot is online!

## STEP 8: Downloading plugins!
(you do not need this part if you do not use plugins)
If you installed plugins, you need to download git and doing step 7 again!
You have to use git to download plugins! You can download git by clicking [here!](https://git-scm.com/)

```CREDITS```
Writer: Elflanded
Original Post: https://taaku18.github.io/modmail/local-hosting/

``EXTRA INFO``
If you're having trouble join the modmail discord server! https://discord.gg/CdBHBs

