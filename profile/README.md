<img align="right" src="https://ccdexplorer.io/static/apple-touch-icon.png" height="60"></img>
# CCDExplorer.io

Welcome to the CCDExplorer Universe.


There are 3 user-facing services:
1. [ccdexplorer.io (the site)](#ccdexplorer-site)
2. [api.ccdexplorer.io (the api)](#ccdexplorer-api)
3. [notifications (the bot)](#ccdexplorer-bot)

There are 5 non user facing services that enable this:
1. [ccdexplorer-heartbeat](#ccdexplorer-heartbeat)
2. [ccdexplorer-recurring](#ccdexplorer-recurring)
3. [ccdexplorer-paydays](#ccdexplorer-paydays)
4. [ccdexplorer-nightly-accounts](#ccdexplorer-nightly-accounts)
5. [ccdexplorer-statistics](#ccdexplorer-statistics)

## ccdexplorer-site
Todo.

## ccdexplorer-api
Todo.

## ccdexplorer-bot
Todo.

## ccdexplorer-heartbeat
This repo is the `heartbeat` of CCDExplorer Universe, filling the db with blocks, transactions and much more. Please visit [the repo](https://github.com/ccdexplorer/ccdexplorer-heartbeat/blob/main/README.md) for more information.

## ccdexplorer-recurring
This repo contains methods that execute queries on a schedule, to shift workload form the user-facing services. Results are stored in separate collections in the db. Please visit [the repo](https://github.com/ccdexplorer/ccdexplorer-recurring/blob/main/README.md) for more information.

## ccdexplorer-paydays
This repo contains code that runs on a daily basis to calculate the effects of paydays on delegators and validators. Repo to be shared later.





More repos to be added at a later stage.