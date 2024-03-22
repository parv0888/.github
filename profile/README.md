<img align="right" src="https://ccdexplorer.io/static/apple-touch-icon.png" height="60"></img>
# CCDExplorer.io

Welcome to the CCDExplorer Universe.


There are 3 user-facing services:
1. [ccdexplorer.io (the site)](#ccdexplorer-site)
2. [api.ccdexplorer.io (the api)](#ccdexplorer-api)
3. [notifications (the bot)](#ccdexplorer-bot)

There are 8 non user facing services that enable this:
1. [ccdexplorer-heartbeat](#ccdexplorer-heartbeat)
2. [ccdexplorer-recurring](#ccdexplorer-recurring)
3. [ccdexplorer-paydays](#ccdexplorer-paydays)
4. [ccdexplorer-accounts-retrieval](#ccdexplorer-accounts-retrieval)
5. [ccdexplorer-nightrunner](#ccdexplorer-accounts)
6. [ccdexplorer-nightrunner](#ccdexplorer-nightrunner)
7. [ccdexplorer-recurring](#ccdexplorer-recurring)
8. [ccdexplorer-fundamentals](#ccdexplorer-fundamentals)
 
## ccdexplorer-site
Please visit [the repo](https://github.com/ccdexplorer/ccdexplorer-site/blob/main/README.md) for more information.

## ccdexplorer-api
Please visit [the repo](https://github.com/ccdexplorer/ccdexplorer-api/blob/main/README.md) for more information.

## ccdexplorer-bot
Please visit [the repo](https://github.com/ccdexplorer/ccdexplorer-bot/blob/main/README.md) for more information.

## ccdexplorer-heartbeat
This repo is the `heartbeat` of CCDExplorer Universe, filling the db with blocks, transactions and much more. Please visit [the repo](https://github.com/ccdexplorer/ccdexplorer-heartbeat/blob/main/README.md) for more information.

## ccdexplorer-recurring
This repo contains methods that execute queries on a schedule, to shift workload form the user-facing services. Results are stored in separate collections in the db. Please visit [the repo](https://github.com/ccdexplorer/ccdexplorer-recurring/blob/main/README.md) for more information.

## ccdexplorer-paydays
This repo contains code that runs on a daily basis to calculate the effects of paydays on delegators and validators. Please visit [the repo](https://github.com/ccdexplorer/ccdexplorer-paydays/blob/main/README.md) for more information.

## ccdexplorer-nightrunner
This repo contains code that runs on a nightly basis, mainly preparing statistics. Please visit [the repo](https://github.com/ccdexplorer/ccdexplorer-nightrunner/blob/main/README.md) for more information.

## ccdexplorer-accounts-retrieval
This repo contains code that runs on a nightly basis to retrieve all accounts as of the last block of the day. Please visit [the repo](https://github.com/ccdexplorer/ccdexplorer-accounts-retrieval/blob/main/README.md) for more information.

## ccdexplorer-accounts
This repo contains the nightly accounts as of the last block of the day. Please visit [the repo](https://github.com/ccdexplorer/ccdexplorer-accounts/blob/main/README.md) for more information.


## ccdexplorer-fundamentals
This repo contains Shared code used by all other repos, including the Python GRPC SDK Please visit [the repo](https://github.com/ccdexplorer/ccdexplorer-fundamentals/blob/main/README.md) for more information.





More repos to be added at a later stage.
