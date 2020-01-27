# How to contribute xerl
You can propose any command by making pull request to this repo.
Fork this repo, then add file "your-command.js" with your NodeJS code for command.
Libraries used: NodeJS, DiscordJS. But you can use any library from npm - we'l install this library.
Command function - module.exports in command file. This function takes two arguments - args and message.
Example - file named "ping.js" with following content:
```javascript
module.exports=(args,message)=>{
message.reply("pong!")
})
```
Thanks for contributing this bot!

Discord: https://discord.gg/S3kxatV

Invite: https://discordapp.com/api/oauth2/authorize?client_id=540187298403450891&permissions=1010159041&redirect_uri=https%3A%2F%2Fdash.xerlbot.icu%2Fauth&scope=bot
