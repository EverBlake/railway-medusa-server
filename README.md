<div align="center">
  <a href="https://medusajs.com" target="_blank" rel="noopener">
    <img alt="Medusa" src="/logos/maedusa_js.png" width="120" />
  </a>
  <span>&nbsp;&nbsp;</span>
  <a href="https://medusajs.com" target="_blank" rel="noopener">
    <img alt="Medusa" src="/logos/railway_app.png" width="120" />
  </a>

# Medusa + Railway Template

**This repo provides a super fast way to get started using <a href="https://medusajs.com" target="_blank" rel="noopener">Medusa</a> on <a href="https://railway.app" target="_blank" rel="noopener">Railway</a>**

Build a headless e-commerce store the open-source way with Medusa (the open-source Shopify alternative) and Railway (infrastructure, instantly).

<br />

Deploy your own Medusa server by clicking this button:

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/0DaHVH?referralCode=QB7L2P)

<br />

This template will automatically build everything you need to get started:

A Redis database ✅

A PostgresSQL database ✅

And a clone of the Medusa server ✅

So there is no need to setup a database locally! 🎉
<br />

</div>

<br />

## Environment variables

When using this template you will be asked for the following environment variables:

```EditorConfig
PORT=9000
COOKIE_SECRET=changeme
JWT_SECRET=changeme
DATABASE_URL=changeme
REDIS_URL=changeme
```

During setup on Railway these variables can be set to anything as above, then updated after install.

For local development `PORT` should be set to `9000`, unless you have changed the default values.

`DATABASE_URL` and `REDIS_URL` will then need to be updated to the database urls after setup is complete.

### Set the `DATABASE_URL` variable with the Postgres Connection url

1. Click on the PostgreSQL card.
2. Choose the Connect tab.
3. Copy the Postgres Connection URL.
4. Click on the GitHub repository’s card.
5. Choose the Variables tab.
6. Set the `DATEBASE_URL` value by pasting in the URL.

### Set the `REDIS_URL` variable with the Redis database url

1. Click on the Redis card.
2. Choose the Connect tab.
3. Copy the Redis Connection URL.
4. Click on the GitHub repository’s card.
5. Choose the Variables tab.
6. Set the `REDIS_URL` value by pasting in the URL.

For the Medusa docs explaining this setup (without this template) see: <a href="https://docs.medusajs.com/deployments/server/deploying-on-railway" target="_blank" rel="noopener">https://docs.medusajs.com/deployments/server/deploying-on-railway</a>.

<br />

## Links

**Note:** This repo only contains the backend server for Medusa, to create a full Medusa powered e-commerce store you will also need a storefront and admin both of which can be hosted on <a href="https://www.netlify.com" target="_blank" rel="noopener">Netlify</a>.

### Repos

Medusa admin: <a href="https://github.com/medusajs/admin" target="_blank" rel="noopener">https://github.com/medusajs/admin</a>

Gatsby storefront starter: <a href="https://github.com/medusajs/gatsby-starter-medusa" target="_blank" rel="noopener">https://github.com/medusajs/gatsby-starter-medusa</a>

Next.js storefront starter: <a href="https://github.com/medusajs/nextjs-starter-medusa" target="_blank" rel="noopener">https://github.com/medusajs/nextjs-starter-medusa</a>

### Full Documentation

Medusa's docs: <a href="https://docs.medusajs.com" target="_blank" rel="noopener">https://docs.medusajs.com</a>

Railway's docs: <a href="https://docs.railway.app" target="_blank" rel="noopener">https://docs.railway.app</a>
