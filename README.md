## What is it?

This is a demo repository corresponding to the Mage ETL demo [here](http://docs.mage.ai/guides/load-api-data).

This demo pulls data from an API, transforms it with Mage, and writes it to a local DuckDB database.

## How can I get started?

First, be sure Docker is installed and running, then run the following command:

Mac/Linux:

```bash 
git clone https://github.com/mage-ai/etl-demo mage-etl-demo \
&& cd mage-etl-demo \
&& cp dev.env .env && rm dev.env \
&& docker compose up
```

Windows:

```bash 
git clone https://github.com/mage-ai/etl-demo mage-etl-demo 
cd mage-etl-demo
cp dev.env .env
rm dev.env
docker compose up
```