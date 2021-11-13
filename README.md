# MoralisTuts
A place to learn Moralis

## What is Moralis?

Moralis is the fastest way to build and deploy dApps on Ethereum, BSC, Polygon, Solana, and Elrond (more coming). All Moralis dApps are cross-chain by default. Building on Moralis ensures that your dApp is future-proof. Even if new blockchains are invented, your dApp will instantly work on any chain.

What are Moralis Servers?

At the core of every dApp built with Moralis is a Moralis Server. Together with the Moralis SDK, it's what allows you to quickly create a dApp with user authentication and blockchain data such as user token balances, NFTs, transactions, and events.

Let's quickly summarize the different components of a Moralis Server that you will be using.

## Database

Here is where all of your data will be stored. For example, when a user signs in to your dApp using [crypto wallet authentication](https://docs.moralis.io/moralis-server/users/crypto-login), that wallet address will automatically be saved to your database together with any data you have configured, such as token balances, historical transactions, or events.

You can then use this data instantaneously in your dApp frontend.

You can read more under the sections: [Moralis Server Database](/moralis-server/database) and [User Authentication](/moralis-server/users/crypto-login).

## Cloud Code

If you need to execute backend code in your dApp, you can do so by using [Moralis' Cloud Code](/moralis-server/cloud-code) feature. Maybe you need to do aggregation or filtering on data that requires computation on the backend. By using cloud code, you can write functions in JavaScript, which can then be triggered by either calling it from your dApp, when certain events happen or triggered by a scheduled job.

You can read more about this in the [cloud code section](/moralis-server/cloud-code).

## The Moralis SDK

Moralis' SDK is how we tie all of this together. Our JavaScript SDK is how your dApp interacts with your Moralis Server. Using the SDK, you can authenticate users, either through username and password or through a crypto wallet like MetaMask You can also use the SDK to get and set user data to fetch balances, NFTs, events, or transactions.

You can read more about the SDK by [clicking here](https://docs.moralis.io/moralis-server/getting-started/connect-the-sdk).
