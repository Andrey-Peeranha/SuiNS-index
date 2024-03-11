# It’s time to .move! [Part 1/4: Front-End Attacks]

When we embarked on the journey of building a Name Service on Sui, we wanted to be different. We believe just like the Sui blockchain itself, pride comes from being unique and disruptive in your own right.

We noticed early on that Name Services on the blockchain were intended to be a decentralized form of DNS. Where DNS is typically used to represent companies, entities and organizations on the internet. However in practice we saw that most Name Services were being adopted as web3 usernames. For SuiNS we wanted to develop two key products based on our user vs. company observation: Names focused on specific use cases with added utility.

Our .sui names are built for users. This is your web3 username. Individuals that own a wallet or set of wallets on Sui can represent their identity with a simple name (e.g. sean88.sui) instead of a complicated series of letters and numbers. Our .sui service simplifies your identity on the blockchain and how you send and receive tokens. SuiNS .sui names will deliver much more utility when it comes to GameFI, but for now we’ll keep those secrets for a future article.

Our .move names are built for companies and projects that have a presence on the blockchain. Just like .sui name points to wallet addresses, .move names point to contracts on the blockchain. They represent a project or companies presence on Sui and what contracts they own.

This design has unique implications of how users will interact with blockchains in the future!

## Front-End Attacks
On blockchain platforms a very common occurrence (and unfortunate one) is that users fall victim to hacks. One common way hacks occur are through front-end attacks. Let’s show you an example, and talk about our friend Bob.

Bob has just found a link to a NFT collection that someone has messaged him on Discord. Now Bob knows he shouldn’t follow the link but he’s heard of this collection before, and it’s a real collection his friends made money on! Let’s call it Sui Scorpions.

It’s late at night, Bob’s had a little too much to drink, and instead of asking his friends for the websites official address, he decides to follow the link and try minting a Sui Scorpion, after all they are on sale!

Most NFT collectors have the experience of going to a website and minting a NFT. How does that process work? You go to the website, find the mint button and press it. Your wallet pops up and all you see is how much you will spend and a contract address:

0x07b7379713288f6a017112c195435cfd762d2eee

Now for most users in blockchain, they don’t necessarily know how to tell if the contract is correct. They know they are at the right website, so it should be safe, shouldn’t it? Not always.

It is certainly possible that you are at the wrong website, either by following a bad link or typing the name in wrong. But there could also be what’s called a front-end attack. A malicious user who has either hacked into the website, or an employee that has gone rogue. In either case they have changed the contract address so it can drain your funds!

With the .move service from SuiNS, you are able to see a simple, human-readable name instead of the contract address. If the NFT project has registered a .move domain, they will have the ability to integrate directly within the wallets to show verification.

So instead of seeing:

0x07b7379553288f6a017112c195435cfd762d2eee

You see:

nft.suiscorpions.move

The first address is actually a malicious contract. However if the contract was correct, you would see it registered as: nft.suiscorpions.move. and a verification symbol (with verification level) in your wallet UI. The SuiNS website will provide details about the verification, the company or project, and whether the contract has been audited. Everyone on the internet has worked with services like this before. They are called “Certificate Authorities” which verify that the website you are interacting with is correct.

We are taking this concept to the next level by partnering with many of the key players in the Sui ecosystem to deliver a end-to-end system utilizing the latest and greatest trustless technologies.

From a verification perspective we are partnering with zCloak (https://zcloak.network/) to provide zero-knowledge proof technology to our users. This will allow entities to provide verification through a user generated proof as opposed to providing the raw data. With Zcloak’s help we will have options for allowing verification for anonymous projects (twitter, website, email) all the way to verifications such as lawyer attestation that fully verifies a companies presence in real life and on the blockchain. Along with support from our good friends throughout the Sui Wallet Ecosystem and Security and Data platforms, we have commitment from the following partners to integrate directly:

Ethos Wallet (https://ethoswallet.xyz/)

Martian Wallet (https://martianwallet.xyz/)

Morphis Wallet (https://morphiswallet.com/)

Suiet Wallet (https://suiet.app/)

Glass Wallet (https://glasswallet.app/)

Surf Wallet (https://surf.tech/)

OKX Web3 Ecosystem (Q1 2023)

Marble Wallet (Coming soon to Sui) (https://marblewallet.com)

Wave Wallet (https://wavewallet.app)

Fewcha Wallet (https://fewcha.app/)

Coin98 Wallet (Coming soon to Sui) (https://wallet.coin98.com/)

And the following security companies:

OtterSec (https://osec.io)

Zokyo (https://www.zokyo.io/)

MoveBit (https://www.movebit.xyz/)

and data companies:

Suiscan (https://suiscan.xyz/)

We believe in a blockchain experience that is safe and simple, with your NFTs and tokens staying where they should be: in YOUR wallet! Please stay tuned for our next article in this 4 part series, where we discuss other new and innovative way to use the .move service!
