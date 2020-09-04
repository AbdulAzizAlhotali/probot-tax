# Welcome To Probot Tax Package
in this package i show you how to create probot tax command

# Installation
`npm i probotax --save`

# How To Use

For Example in discord.js
```
const probot = require("probotax");
client.on("message", message => {
    if(message.content.startWith(prefix + 'tax')) {
        message.channel.send(probot.taxs(10))
    }
})
```

