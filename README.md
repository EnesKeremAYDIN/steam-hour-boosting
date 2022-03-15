[![Steam](https://img.shields.io/badge/donate-steam-blue?logo=Steam&style=flat-square)](https://steamcommunity.com/tradeoffer/new/?partner=434566573&token=g789u6Uv)
[![Discord](https://discord.com/api/guilds/817779288296128512/widget.png)](https://discord.gg/fJGtmKbuQB)  
[steam-hour-boosting](https://github.com/EnesKeremAYDIN/steam-hour-boosting)

# Setup:

## If the account has Steam Guard (recommended)
* Get Steam guard shared secret with [SDA](https://github.com/Jessecar96/SteamDesktopAuthenticator). (Or [Android](www.google.com/search?q=how+to+get+rooted+android+steam+guard+code), with [IOS](www.google.com/search?q=how+to+get+rooted+android+steam+guard+code)) (location: sda_folder/maFiles/<account_64_id>.maFiles)
* Enter the username, password and shared secret the account on lines 6, 7 and 8 in the bot.js file.
* Delete the double slash (//) at the beginning of line 8.
* Enter the sample app id list from line 13 in the bot.js file. (enter up to 32 ids!)
* Upload to a cloud service or leave it open on your computer.

## If the account does not have Steam Guard
* Enter the username and password of the account on lines 6 and 7 in the bot.js file.
* Enter the sample app id list from line 13 in the bot.js file. (enter up to 32 ids!)
* Upload to a cloud service or leave it open on your computer.

## Cloud service recommendation (Heroku)
* Open a Heroku account. https://signup.heroku.com
* Verify your Heroku account. (required for uninterrupted use) https://devcenter.heroku.com/articles/account-verification
* Open a GitHub account. https://github.com/signup
* Come to this [repo](https://github.com/EnesKeremAYDIN/steam-hour-boosting), click the star in the upper right. ⭐
* Upload your own account's codes to GitHub. https://docs.github.com/en/get-started/quickstart/create-a-repo
* Link your GitHub account and project to your Heroku account. https://devcenter.heroku.com/articles/github-integration
* Deploy the codes to your Heroku account. https://devcenter.heroku.com/articles/github-integration

## Warnings:
* There are a lot of people using this system, a lot of them, and I haven't seen any of them penalized by Steam or Valve, but that doesn't mean they won't (I don't think they will). In short, all responsibility is on you when using it, if you do not accept all risks, do not use it.
* When entering the list of IDs, put a comma (,) at the end of all IDs except the last ID.
* Make the repo you uploaded to your GitHub account private.

I'll be posting an update soon that will let you manage this bot via Discord, I guess.
