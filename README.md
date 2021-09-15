# Discord Music Bot
An open-source discord music bot that uses discord-player to play music. 

# Getting Started
> Make sure you have Node v14x installed on your pc. To check node.js version:
```javascript
node -v
```
If you do not have Node installed in your pc; you can install it from [here](https://nodejs.org/en/download/)

# Insallation
```javascript
git clone https://github.com/redleague/discord-music-bot.git
cd discord-music-bot
npm install
```

# Configuration
Open `config.js` file in any text editor.

```javascript
module.exports = {
  token: "Your bot token", //make sure you replace it with yours bot token
  prefix: "-",
  supportServer: (code) => `https://discord.gg/${code}`,
  inviteURL: (id, permissions) => `https://discord.com/api/oauth2/authorize?client_id=${id}&permissions=${permissions ? permissions : '8'}&scope=bot`,
}
```

# Features
- Easy to use
- Open Source

# Inportant
> This project is not fully completed yet. If you wana support this project you can join discord server [Click here](https://discord.gg/25js8gwYNX)


