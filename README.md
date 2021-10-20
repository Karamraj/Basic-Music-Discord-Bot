# Basic-Music-Discord-Bot
Just a basic music bot coded in Javascript and has 10+ commands 🎧

Click [here](https://discord.gg/8ZWYaUpvxb) to join Electric Development Hub, a server which helps connecting developer and also aim in spreading culture of coding.

### ⚡ Installation

Well, let's start by downloading the code.
Go to the folder `config` then the file `bot.js`.
For the bot to be able to start, please complete the file with your credentials as follows :


- For configuration

```js
discord: {
    token: '--TOKEN--',
    prefix: '--PREFIX--',
    activity: '--ACTIVITY--',
}
```

- `token`, the token of the bot available on the [Discord Developers](https://discordapp.com/developers/applications) section.
- `prefix`, the prefix that will be set to use the bot.
- `activity`, the activity of the bot.

In the console, type `npm install` to install all dependencies.

- To start the bot :

```
#With Node

1. npm install
2. node index.js
```

All you have to do is turn on your bot !

### 🎵 Music commands

```
-> play <name/URL>, play music in a voice channel.
-> search <name>, open a panel to choose a music and then play it.
-> pause, pause the current music.
-> resume, puts the current music back on.
-> queue, see the next songs.
-> clear-queue, remove music in the queue.
-> shuffle, to mix the queue.
-> nowplaying, see music in progress.
-> loop, to enable or disable the repeat function.
-> volume <1 - 100>, change the volume.
-> skip, skip to next music.
-> stop, stop all music.
```

### 💡 General commands

```
ping, see the bot latency.
help, see the list of available commands.
debug, see number of voice connections.
```

### 🏓 Developer


This is proudly coded by Luther#5412. Make sure to join [Electric Development Hub](https://discord.gg/8ZWYaUpvxb).
