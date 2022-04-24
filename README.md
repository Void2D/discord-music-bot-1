![Github Stars](https://img.shields.io/github/stars/nottmayank/discord-player-bot?style=for-the-badge&logo=appveyor)
![GitHub issues](https://img.shields.io/github/issues-raw/nottmayank/discord-player-bot?style=for-the-badge&logo=appveyor)

# 🎵 Discord Music Bot 
An open-source discord music bot that uses discord-player to play music

# 🚀 Getting Started
> Make sure you have Node v12x installed on your PC. To check node.js version:

```
node -v
```
If you do not have Node installed in your PC; you can install it from [here](https://nodejs.org/en/download/)

# 💨 Insallation
> Make sure Git is installed on your PC or download ZIP
```
git clone https://github.com/redleague/discord-music-bot.git
cd discord-music-bot
npm install
```

# 🧠 Configuration
* Open `config.js` file in any text editor
* Add your bot's token
* Change prefix according to your need

```javascript
module.exports = {
  token: "Your bot token", //make sure you replace it with yours bot token
  prefix: "-",
  supportServer: (code) => `https://discord.gg/${code}`,
  inviteURL: (id, permissions) => `https://discord.com/api/oauth2/authorize?client_id=${id}&permissions=${permissions ? permissions : '8'}&scope=bot`,
}
```

# 💫 Features
* ✅ Easy to use
* ✅ Open Source
* ✅ No need to setup anything
* ✅ Multiple guild support



