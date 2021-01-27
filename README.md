# discordjs-heroku-demo
A demo of a Discord bot using DiscordJS deployed to Heroku

To run this bot locally, you need to have NodeJS installed.

Setup:
1. Setup environment variables:
    * **Development environment:**
      Create a `.env` file to repository root with:
      ```
      DISCORD_TOKEN=YOUR_DISCORD_BOT_TOKEN_HERE
      ```
    * **Production environment (for example Heroku)**
      Set local environment variables `NODE_ENV=production` and `DISCORD_TOKEN=YOUR_DISCORD_BOT_TOKEN_HERE`
2. Run the bot with `node bot.js`
