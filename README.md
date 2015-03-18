# Follow Back Bot
A Twitter Bot written in python that automatically follows anyone currently following the bots account.

## Installation
The bot was written in Python so to run the bot you need to have python installed.  Python can be downloaded from http://www.python.org

The twitter bot uses Tweepy to access and use the Twitter API.  You can find information about Tweepy and a link to the Tweepy Documentation at http://www.tweepy.org

Tweepy can be installed using:
```
pip install tweepy
```

## Usage
To run this bot open a command line, navigate to the directory containing the script and run:
```
python FollowBack.py
```

## Automation
If you wish to automate this bot the method I used was to setup a cron job on a VPS that ran the script every 4 hours
