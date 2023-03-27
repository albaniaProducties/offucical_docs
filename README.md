# Documentation
- The library is made on the BASIS of others, there were no carbon copies.
- Not to say that this is the "best" library for those who want to write bots without bothering with the discord.js methods.
# Census in progress
- **What does that mean?**
- This is when we change methods, and add them, fix bugs. In general, updates are only global in scale.
# Bot usage example:
```js const { Bot, MessageEmbed } = require('are-disocrd');
// depending on what you write after const, a lot will change. If you change bot to client, botik or generally "bsbebeheueueudjdjd_bdbdbdbd" you will have to change this wherever the bot is used.
const bot = new Bot({
prefix: "!",
intents: 3276541 });
bot.command({
name: "ping",
run: (client, message, args) => {
const pings = MessageEmbed()
.setTitle('delay');
.setDescription(`Hello <@${getId}>, my delay: ${bot.ping}`)
.setColor('#F0000')
message.reply({ embeds: [ping] });
bot.start('your appliaction token');

// then change the concept of commands :D
```
