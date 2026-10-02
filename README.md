# Rustic 301 via Dockerized Nginx

[![MIT](https://img.shields.io/github/license/MieuxVoter/don.mieuxvoter.fr?style=for-the-badge)](./LICENSE)
[![Join the Discord chat at https://discord.mieuxvoter.fr](https://img.shields.io/discord/705322981102190593.svg?style=for-the-badge)](https://discord.mieuxvoter.fr)


Sets up a 301 redirect.

> We use this to provide a permalink to our donation service.
> 
> https://don.mieuxvoter.fr → https://www.paypal.com/donate/?hosted_button_id=QD6U4D323WV4S


## How to use

1. Copy the `.env.dist` file to `.env`:
   ```sh
   cp .env.dist .env
   ```

2. Then, configure `.env`.
3. Run docker compose:
   ```sh
   docker compose up
   ```
