<div align="center">
  <br />
  <p>
    <a href="https://github.com/mafineeek/des-games-super"><img src="https://github.com/mafineeek/des-games-super/blob/main/assets/des-games.png" width="546" alt="des-games" /></a>
  </p>
  <br/>
  <p>
    <a href="https://www.npmjs.com/package/des-games-super"><img src="https://img.shields.io/npm/v/des-games-super.png?maxAge=3600" alt="NPM version" /></a>
    <a href="https://www.npmjs.com/package/des-games-super"><img src="https://img.shields.io/npm/dt/des-games-super.png?maxAge=3600" alt="NPM downloads" /></a>
  </p>
</div>

## Welcome
<b>Welcome! This 'des-games' module!</b><br>
<b>This is a powerful game addon for Discord Economy Super.</b>

## Installation

**Please note: Node.js 14.0.0 or newer is required.<br>
All types in brackets mean the type of what the method or event returns.**

Install [des-games-super](https://www.npmjs.com/package/des-games-super)
```JS
$ npm install des-games-super
```

## Features

* Simple & easy to use 👍
* Beginner friendly 😄
* Module base support 📃

## Module Managers
- 'UtilsManager' - <b>Manager that enables module Utils.</b>

## Module Constructor Options
- 'options.fishConfig.cooldown' - <b>Property responsible for the amount of time between games.</b>
- 'options.fishConfig.maxAmount' - <b>Property responsible for the maximum amount of rewards for the game.</b>

- 'options.huntConfig.cooldown' - <b>Property responsible for the amount of time between games.</b>
- 'options.huntConfig.maxAmount' - <b>Property responsible for the maximum amount of rewards for the game.</b>


## Quick Initialization Example

```JS
const Discord = require('discord.js');

const client = new Discord.Client();
const Economy = require('discord-economy-super');
const eco = new Economy();
const EconomyGames = require('des-games-super');
const games = new EconomyGames(eco);

client.on('ready', () => {
  console.log('Bot started!');
})

client.login('YOUR_BOT_TOKEN_HERE');
```


# Useful Links

* Module fix: [mafineeek](https://github.com/mafineeek)
* Original Module Developer: [xyligan](https://www.npmjs.com/~xyligan)
* Developer Discord: [mafineeek.#0001](https://discord.com/users/854342480019587133)
* NPM: [Click](https://www.npmjs.com/package/des-games-super)
* GitHub: [Click](https://github.com/mafineeek/des-games-super)
* Discord: [Click](https://discord.gg/JPhHHtNaJk)

<h1>Thanks for using DES Games Super ♥</h1>