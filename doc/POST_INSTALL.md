## Log in to Slack

In your Matrix client, start a direct chat with `@__BOTNAME__:__SERVER_NAME__` (if it isn't found in the user directory, type the full ID). Use an **encrypted** chat if possible, since you will send credentials in it.

Send `login` to the bot and choose: your email (Slack sends a confirmation code), an auth token and cookie from the Slack web app, or a Slack app (bot and app tokens).

Once logged in, your conversations appear as Matrix rooms. Useful commands: `help`, `list-logins`, `logout <login ID>`. Logs: `sudo yunohost service log __APP__`.
