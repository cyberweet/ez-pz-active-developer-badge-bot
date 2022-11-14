1. Install Node.js (optionally Git)
2. Clone repo or download via ZIP
3. Rename .env.example to .env
4. Create bot application on discord
5. Copy over token and client ID into the .env file
6. Invite bot to server with application command permissions `https://discord.com/oauth2/authorize?client_id=INSERT_CLIENT_ID_HERE&scope=bot&permissions=2147485696`
7. Run `npm i`
8. Run `node deploy-commands.js`
9. Run `node index.js`
10. In your Discord server with the bot and community enabled, run /ping
11. ...
12. Profit???

This is entirely referenced off of https://discordjs.guide/#before-you-begin to show people how easy it is to get a Discord Active Developer Badge. Go learn something new!