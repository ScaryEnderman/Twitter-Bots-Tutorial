Twitter-Bots-Tutorial
=====================

# Twitter Bots using mispy's framework


## STEP 1 - Ruby
```
> First you need to install Ruby. Best way is by downloading from http://railsinstaller.org/en.
```


## STEP 2 - Setup
```
> Go to Mispy's framework -> https://github.com/mispy/twitter_ebooks,
and download the .ZIP via the download button on the right side.

> On the side there is a tutorial for setting up your bot.
```


## STEP 3 - Twitter Account
```
> Create your bot's Twitter account. (You will need to confirm your email!)

> Go to https://dev.twitter.com/apps/ and log in with your new account.

> Create a new app, go to 'Permissions' Tab and choose 'Read and Write'.

> Go to the Tab 'API Keys' and here you can generate your access token.

> Now copy 'API Key', 'API secret', 'Access token' and 'Access token secret',
pass them into bots.rb as string into: (Don't share them with anybody)
```
``` ruby
  bot.consumer_key = "" # Your app consumer key
  bot.consumer_secret = "" # Your app consumer secret
  bot.oauth_token = "" # Token connecting the app to this account
  bot.oauth_token_secret = "" # Secret connecting the app to this account
```


## STEP 4 - Bot's Code
```
> Write your first bots code, just edit bots.rb, which requires a bit of coding knowledge. :)

> Twitter Bot examples for this can also be found on https://github.com/mispy/twitter_ebooks.
```


## STEP 5 - Heroku
```
> Go to http://heroku.com/ and create an account.

> Install Heroku's Toolbelt: https://toolbelt.heroku.com/
(Further Information: https://devcenter.heroku.com/articles/quickstart)
```

## STEP 6 - First Bot on Heroku
```



```
