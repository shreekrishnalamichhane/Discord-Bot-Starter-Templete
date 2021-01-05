## Steps for the configuration.

- Create a bot application through the [discord developers portal](https://discord.com/developers/applications).
- Once the application is created , convert it to the bot by going it to the bot section in the sidebar.
- Copy the client id from the General Information tab and then go to this [link](https://discordapi.com/permissions.html) to calculate the permission and then add to your server. For that choose the permissions you need and then paste the copied client id in the bottom. It will generate the link from which you can login your bot and add to the server.
- After that copy the bot sercet token and paste it in the .env file of the project.
- Finally type `npm run dev` on the commandline to start with node server with nodemon.

If everythings goes right then you should be online in the server.
