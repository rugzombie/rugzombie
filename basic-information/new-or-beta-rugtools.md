# ⚙ NEW | Beta RugTools!!!

## RugTools Messaging Service

Welcome to RugTools (Beta). RugZombie does not desire to deliver services ONLY post-mortem, after a rugpull or hack, but as we mutate, we are excited to offer a suite of services to keep users and projects safe as they interact in web3.

How can you use the service? \
\- Send VERIFIED messages on the chain

\-In emergencies, if your social accounts are hacked, you can send on-chain messages

\-Verify messages through the rugtools portal

### What is Safe Message w/ RugToolsBot?

Problem: While smart contracts can remain reasonably safe due to the security offered by the blockchain, as web3 projects use web2 tools such as discord, twitter, etc, authority accounts such as these are being hacked and users subsequently phished in social engineering attacks.&#x20;

Solution: Safe Message by RugTools! By leveraging on-chain messaging, RugTools allows NFT and token project owners on the BNBChain (more chains to come) to send secure messages that are publicly auditable on the blockchain .

Our telegram bot and discord bot are currently live. By registering with Safe Message, you can send messages on-chain that will publish to your telegram and can be found by visiting our [tools page](https://tools.rugzombie.io/messaging/admin).&#x20;

## Setting up your RugToolsBot

The setup process is meant to be simple, straightforward. How you choose to use and deploy the service is really up to you. Remember, discord and telegram are still web2 tools, but our key difference is that these messages are verifiable on the chain.&#x20;



### Registering Bot with Telegram

1. Add the Rug Tools bot to your group (https://t.me/RugToolsBot @RugToolsBot)&#x20;
2. Start the registration process in the chat /register \<wallet\_address> bsc (leave out the <>)
3. The bot will respond back with a registration code&#x20;
4. Go to [https://tools.rugzombio.io/messaging/admin ](https://tools.rugzombie.io/messaging/admin)
5. Connect your wallet and use the form to set your registration code in the contract&#x20;
6. Once the code is set, the bot will pick that up within the next minute and a message will be broadcast to the group advising the wallet has been added as a messaging source

### Registering Bot With Discord&#x20;

1. Add the Rug Tools bot to your Discord server by going to this URL https://discord.com/api/oauth2/authorize?client\_id=1012407324675166291\&permissions=3072\&scope=bot&#x20;
2. This will give the bot permission to read and send messages on the server only&#x20;
3. Go to the text channel in your server that you want the bot to and do the /register command which will open this dialog
4. Fill out the wallet and chain fields and submit the command Chains: bsc&#x20;
5. The bot will respond back with a registration code&#x20;
6. Go to [https://tools.rugzombio.io/messaging/admin ](https://tools.rugzombie.io/messaging/admin)
7. Connect your wallet and use the form to set your registration code in the contract
8. &#x20;Once the code is set, the bot will pick that up within the next minute and a message will be broadcast to the group advising the wallet has been added as a messaging source

### Sending Messages&#x20;

1. Go to [https://tools.rugzombie.io/messaging ](https://tools.rugzombie.io/messaging/admin)
2. Connect your wallet and use the form to submit a message to the blockchain&#x20;
3. Once the transaction is complete, the bot will pick up the message within the next minute and broadcast it out to any channels on Discord or Telegram that have been previously registered

### Reading Messages

1. Go to [https://tools.rugzombie.io/messaging](https://tools.rugzombie.io/messaging/admin)
2. Connect your wallet (needed to get the blockchain ID from)&#x20;
3. Use either the alias or wallet address search to pull up all the messages sent by the address

### Set Wallet Alias&#x20;

1. Go to [https://tools.rugzombie.io/messaging/](https://tools.rugzombie.io/messaging/admin)
2. Connect your wallet&#x20;
3. Use the form to submit a new alias name for your wallet address

## !!!Important!!! Announcing to Your Community

As you add these messenger wallets and the bot system to your community. It is important to share this information publicly with your community. We recommend the following:

1. In your white paper, publicly list your messenger wallet address, along with alias .
2. Copy this message on your gitbook or other white paper for users to verify the service:&#x20;

### Safe Messages

{% hint style="info" %}
Our Project Uses 'Safe Messaging' in order to secure our messages on the chain. Safe Messages use a bot service, but you can verify these messages on the blockchain or verify them with the following info:

1. Go to [https://tools.rugzombie.io/messaging](https://tools.rugzombie.io/messaging/admin)
2. Connect your wallet (needed to get the blockchain ID from)&#x20;
3. Use either the alias or wallet address search to pull up all the messages sent by the address
4. Messenger Address:&#x20;
5. Messenger Alias:&#x20;
{% endhint %}

We also recommend a public announcement of using the tool to your community so that they know what they are seeing.&#x20;

#### Service Costs

The RugToolsBot messaging service is intended to be a public utility and therefore as cheap as possible:

Sending on-chain messages requires a gas cost (minimal)&#x20;

To set up the bot and send messages requires a fractional charge or 2$ to setup and .50c per message. These costs support feeding the contract, deploying on new chains and maintaining the bots.&#x20;
