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
