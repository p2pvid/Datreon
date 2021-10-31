# Datreon
## Inspiration
Patreon has been a great tool for Youtubers or any other content creators to get support from their supporters steadily. Patreon is worth over 4 Billion Dollars and is growing fast. But there are lot of problems with it as well. Accessibility at different locations is the big challenge. Credit card and Bank support for Patreon is not available at all locations and countries. What if we can build a Patreon using Blockchain and cryptocurrency such that it will be universally compatible?
## What it does
Datreon is a decentralized version of Patreon. People can get subscription for exclusive content from their favourite creators using Cryptocurrency. All the subscriptions are taken care by Smart Contract deployed in Aurora network which runs on top of NEAR protocol. All of the data and media files uploaded are stored in IPFS network which makes this DApp much more distributed.
## How we built it
Datreon is a web app built using normal Web stack of HTML, CSS, JS. Backend and Smart contracts are written in Javascript and Solidity. Datreon web app is hosted through IPFS using fleek. This lets our Webapp be accessible from anywhere without the problem of having any downtimes. Link can be found below. All of the media is stored in IPFS instead of centralized server for security.
## Challenges we ran into
As our DApp has huge use-case and may encounter large number of transactions we needed a robust network that can handle our transaction requests and maintain lower gas fee. For this we have looked into NEAR protocol. It is suitable and perfect for our application but due to limited knowledge with Rust I've struggled a lot to finish my smart contract, Later we got to know about Aurora network and fully utilized its EVM compatibility feature to finish our smart contract in Solidity.
## Accomplishments that we're proud of
Datreon can have large number of users if further developed and we are really happy with building its initial version successfully with all features. Aurora network really helped us a lot to achieve this. 
## What we learned
I have learned Rust language in the beginning for working with NEAR protocol. Though I couldn't finish building my Contract on it, I still managed to learn a lot. We have never worked on such a complex smart contract before and are glad that we could finish it.
## What's next for Datreon
Datreon currently needs lot of support in terms of frontend. We have built a robust smart contract for managing subscriptions and backend goals are achieved. Frontend needs to be built in much more user friendly manner. Asides from this, Datreon currently supports only few creators to post. This will expanded and all data will be stored in much more efficient decentralized storage like Filecoin.
