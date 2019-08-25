# Evlyn [![Discord](https://discordapp.com/api/guilds/254360814063058944/embed.png)](https://skyra.pw/join)

Evlyn is a private Discord Bot for data retrieval and monitoring.

## Development Requirements

- [`Node.js`]: To run the project.
- [`Ny-API`]: (Dev Optional) Central server.

[`Node.js`]: https://nodejs.org/en/download/current/
[`Ny-API`]: https://github.com/kyranet/Ny-API

## Set-Up

Copy and paste the [`config.ts.example`] file and rename it to `config.ts`, then fill it with the precise variables.
Once all development requirements are set up:

```bash
# Lints and format all the code:
$ yarn lint

# Run Evlyn in development mode:
$ yarn start

# Run Evlyn in production mode, requires
# Ny-API to be running:
$ yarn pm2:start
```

> **Note**: Before pushing to the repository, please run `yarn lint` so formatting stays consistent and there are no
linter warnings.

[`config.ts.example`]: /config.ts.example

# Story

In Skyra's lore, Evlyn is one of the most known healers, recognized for surviving extreme conditions and healed
thousands of injuried soldiers. As a bot, her work reflects her work in the lore: monitor and reviving her teammates.

For the same reason, when Aelia, Alestra, or Skyra, go down, Evlyn is capable of "reviving" them by detecting when they
go down or something goes wrong. Additionally, Evlyn is connected with both units and can offer help with heavy tasks.

## Links

**Evlyn links**

- [Support Server](https://skyra.pw/join)
- [Patreon](https://www.patreon.com/kyranet)

**Framework links**

- [Klasa's Website](https://klasa.js.org)
