# Twitch Betting and Chat Bot

A **Node.js** service that integrates with **Twitch** and **Stream Elements** to run channel betting games and distribute payouts based on event outcomes. It uses **MySQL** for persistence and the Twitch and Stream Elements HTTP APIs.

## Capabilities

- Create and resolve bets tied to live stream events
- Calculate and distribute winnings according to outcomes
- Chat integration via the bot layer

## Stack

- Node.js
- MySQL
- [Stream Elements API](https://streamelements.com/)
- [Twitch API](https://dev.twitch.tv/)

## Setup (overview)

1. Install Node.js and create a MySQL database for the bot’s schema.
2. Configure API credentials (Twitch client ID/secret, Stream Elements token, database URL) via environment variables or a local config file—**do not** commit secrets.
3. Install dependencies and start the process as defined in your entry script (e.g. `npm install` / `node index.js`).

Adjust host, port, and OAuth redirect URLs to match your deployment.

## Disclaimer

This is a personal/educational project. Ensure compliance with Twitch’s developer policy, Stream Elements terms, and gambling regulations in your region.

## License

See the repository license file if present.
