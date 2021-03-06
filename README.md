# AIS API

API to store and retrieve business transaction receipts (configuration, credentials)

## Routes

All routes return Json

- GET `/`: Root route shows if Web API is running
- GET `api/v1/receipts/`: returns all configuration IDs
- GET `api/v1/receipts/[ID]`: returns details about a single receipt with given ID
- POST `api/v1/receipts/`: creates a new receipt

## Install

Install this API by cloning the *relevant branch* and installing required gems from `Gemfile.lock`:

```shell
bundle install
```

## Test

Run the test script:

```shell
ruby spec/api_spec.rb
```

## Execute

Run this API using:

```shell
rackup
```