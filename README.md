# Angular NestJS MetaTrader Project

## Project Architecture

![Angular Dashboard for Meta Trader 4 terminal](https://github.com/kostadin79/angular-nest-metatrader/blob/main/AngularNestMetaTrader.svg)

## Demo

Project demo URL: [https://rcdsolutions.online](https://rcdsolutions.online)
"rcdsolutions.online" is a domain for demo purposes of my personal project.
The domain is required for SSL certificate. Without SSL certificate the Angular service worker cannot be registered.

## Requirements before `docker compose up`

1. MetaTrader4 terminal must be started with MetaTrader4Bridge2.mq4 activated.
   More about that [MQL 4 Folder for ZeroMQ for Meta Trader 4](https://github.com/kostadin79/zeromq-meta-trader)
2. Create docker volume 'SSL' and copy SSL certificates for your public domain and WebSocket
3. Change WS_SOCKET_URL with your NestJS public ip address or domain
4. Change PUBLIC_URL with your public domain
5. Change API_KEY with your password in MetaTrader4Bridge2.mq4
6. Change REQ_URL with MetaTrader terminal ip address
7. Change PULL_URL with MetaTrader terminal ip address

## Links

[Meta Trader 4 with NestJS Socket Gateway](https://github.com/kostadin79/nest-meta-trader)

[Angular UI for MetaTrader with NestJS](https://github.com/kostadin79/angular-meta-trader)
