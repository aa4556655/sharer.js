<div align="center">
      <h1> <img src="https://i.postimg.cc/L4jRM2Xv/sharer.png" width="80px"><br/>sharer.js</h1>
</div>
<p align="center"><a href="https://twitter.com/intent/user?screen_name=ellisonleao" target="_blank"><img alt="Follow me on twitter" src="https://img.shields.io/twitter/follow/ellisonleao?style=flat-square" style="vertical-align:center" /></a> <a href="https://www.jsdelivr.com/package/npm/sharer.js" target="_blank"><img alt="" src="https://data.jsdelivr.com/v1/package/npm/sharer.js/badge" style="vertical-align:center" /></a> </p>

> Using Sharer.js on your project? [Let me know!](https://github.com/ellisonleao/sharer.js/issues/24)

Sharer.js is a very tiny JS library to create custom social share components on DOM elements for your website. No dependencies.

## Documentation

Checkout [the docs page](https://ellisonleao.github.io/sharer.js/) for more info about installing and usage.

## Local n8n setup (Docker + Postgres)

This repo includes a ready-to-run `docker-compose.yml` for running n8n locally with a
persistent Postgres database.

1. Create an environment file:

   ```bash
   cp .env.example .env
   ```

2. Start the stack:

   ```bash
   docker compose up -d
   ```

3. Open n8n at:

   ```
   http://localhost:5678
   ```

To stop the services:

```bash
docker compose down
```
