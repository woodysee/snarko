# Snarko

A really snarky bot made for the Discord chat application, ported over from my own private GitHub repository.

## Get Snarko to work

- Add the environment variables, especially `DISCORD_APP_BOT_TOKEN` along with `SERVER_APP_PORT`, in a new file `.env` with your own implementation.
- Next steps
  - `npm install` to install local packages
  - `npm run build` to build the server app before running
  - `npm start` to run the server app for development (watches for changes)

## Issues

- Can't fast forward tracks added to the playlist
- Need a way to handle multiple guilds
- Hard coded and homebrewed natural language processing that is not as comprehensive as I wanted it to be, could do with a third party library and more research into this area