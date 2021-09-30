<div align="center">
  <h1>Giveawayss</h1>
  <p>
    <a href="https://www.npmjs.com/package/giveawayss"><img src="https://img.shields.io/npm/v/giveawayss?maxAge=3600" alt="NPM version" /></a>
    <a href="https://www.npmjs.com/package/giveawayss"><img src="https://img.shields.io/npm/dt/giveawayss?maxAge=3600" alt="NPM downloads" /></a>
  </p>
  <p>
    <a href="https://www.npmjs.com/package/giveawayss"><img src="https://nodei.co/npm/giveawayss.png?downloads=true&stars=true" alt="NPM Banner"></a>
  </p>
  <p>
    <a href="https://discord.gg/NuNRKKvbPU"><img src="https://discord.com/api/guilds/830627850620108811/widget.png?style=banner2"></a>
  </p>
</div>

## Update 16/9/2021
Discord.JS V13 Update And Embeds Update
## Giveaways
A package for giveaways and drops.
# Drops
Go [here](https://github.com/VidulHB/discord-giveaway/blob/master/README.md#how-to-use-drops) to see how to use the drops.
# 📂 | Installation
```sh
npm install giveawayss
```
# 📜 | Setup
Start by creating a new GiveawayCreator.
```js
const { Client } = require('discord.js');
const client = new Client();
const { GiveawayCreator } = require('giveawayss');
const Creator = new GiveawayCreator(client, 'mongodb://...');

client.giveaways = Creator; // Access the Creator from anywhere.
```
# ✍ | Examples
All Examples Are In The [Documentation](https://docs.giveawayss.cf/)