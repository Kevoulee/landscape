# Non-Fungible Tokens 

---

# Definitions

## Fungible Tokens 

*Fungibility is, essentially, a characteristic of an asset, or token, that determines whether items or quantities of the same or similar type can be completely interchangeable during exchange or utility. It has value and can be used to purchase items with the same or less value*

When a token is fungible is usually means two things:
1. Only the quantity matters
2. Any amount of it can be merged into a larger amount of it- making it undistinguishable from the rest 

## Non- Fungible Tokens 

*Non-fungible tokens (NFTs), are unique in nature and can be distinguished from each other. It is the characteristics of a non-fungible item itself that make it desirable and differentiated, rather than it being a placeholder or representation.*

---

## Function of NFTs

Non-fungible tokens create digital scarcity that can be verified without the need for a centralising organisation of confirm authenticity. 

---
## Types of NFTs 

1. Collectibles
2. Gaming
3. Property 
4. Keys
5. Ticketing

---

## Popular Implementation of NFTs

Example of NFT | Mode of Implementation 
-------------- | ---------------
Rare Pepe | Counterparty 
CryptoKitties |  ERC721
Decentraland | ERC721
CrytoPunks | ERC20
CryptoCelebrities | ?

+++

## Rare Pepe

+++

## CryptoKitties 

* CryptoKitties is a digital collectible game based around cats that are breakable and tradable
* Each cat is unique and individually owned; it cannot be replicated, taken away or destroyed. 
* Each of these cats is represented by a non fungible token on the CryptoKitties smart contract
* CryptoKitties, uses the lesser known ERC721 standard, for non-fungible tokens
* Under this standard, you ensure that each token has its unique attributes and values and that it cannot be substituted for another, making it perfect for solutions that depends on tracking individual units or entities of any kind

+++

## Decentraland 

* Decentraland is a virtual reality platform powered by the Ethereum blockchain
* Users can create, experience, and monetise content and applications
* Land in Decentraland is permanently owned by the community, giving them full control over their creations- creating an immutable record of ownership
* Users claim ownership of virtual land on a blockchain-based ledger of parcels
* Land owners control what content is published to their portion of land, which is identified by a set of Cartesian coordinates (x,y)- Contents can range from static 3D scenes to interactive systems such as games. 
* Decentraland uses an Ethereum smart contract to maintain a ledger of ownership for land parcels in the virtual world 
* Decentraland clients will connect to the Ethereum network to fetch updates to the state of the LAND smart contract
* LAND is bought by burning MANA (MANA can also be used to make in-world purchases of digital goods and services), a fungible ERC20 token of fixed supply
* This token serves as a proxy for the most of claiming a new parcel 
* The LAND contract uses a burn function to destroy MANA and create a new entry in the LAND registry. New parcels need to be adjacent to a non-empty parcel. 

+++

## CryptoPunks 

* The CyptoPunks are 24x24 pixel art images, generated algorithmically
* There are 10 000 unique collectible charaters with proof of owership stored on teh Ethereum blockchain  
* Most are punky-looking characters, but there are a few rarer types mixed in: Apes, Zombies and Aliens
* Every punk has their own profile page that shows their attributes as well as their ownership/for-sale status.  
* Cryptopunks uses a similar system to ERC20 tokens-  the officialt webiste descibes them as "almost ann ERC20 token"
* However, none of the other methods are the same as ERC20 tokens because you’re not transferring a simple balance, but need to reference which specific punk you want to transfer. 

+++

## CryptoCelebrities 

* CryptoCelebrities is the blockchain based game where you can buy, sell, or trade and breed your favourite celebrities that are made and generated over Ethereum blockchain
* It is fully transparent game/system because of being on the Ethereum network. 

---

## The Development of (Non) Fungibe TOken Standards 

* ERC20
* ERC721
* ERC875
* ERC821 
* NEP-5
* NEP-10

+++

## ERC20

* Allows for the implementation of a standard API for tokens within smart contracts
* Provides the basic functionality to transfer tokens
* Allowed tokens to be approved so they can be spent by another on chain third party 

ERC20 is insufficient for tracking NFTs because each asset is distinct (non-fungible), wheares asch of a quantity of tokens is identicl (fungible)

+++

## ERC721

* This standard was drafted by Dieter Shirley 
* This standard provides basic functionality to track and transfer NFTs 

ERC721 is expensive to transfer, as it has to be done one by one, and it lasck a cohesive strategy for efficiently trading each token
These features strain the Ethereum network, when the only way to transfer tokens is one by one, rather than in lots- you can't sell a crytopKitty cheaply- and this creates a lot of congestion 

There needed to be a way to transfer non-fungible tokens in lots and trade in a decentralised safe manner without incurring massive costs 

+++

## ERC875

* It is a new draft standard which allows transferring non-fungible tokens in lots and contains methods to settle orders ina cheap yet equally safe and decentralised manner
* Tokens are stored in arrays and can be transferred in multiples by specfying each token index
* This results in savings and a lower transaction burden on the network as you can move many tokens in one transaction burden on the network

+++

## ERC821

---

## **Ticketing**

The main objective of using non-fungible tokens in the event ticketing industry is to de-silo the industry in a decentralised manner, allowing ticketing applications and promoters to automatically sell tickets for other events and gain commission for doing so. This enables event organisers to reach a wider audience. 

* Thirty percent of all tickets are resold with mark-ups between 30% and 700% 
* The event ticket market is known to be non-transparent, inexplicable transaction costs added to tickets are a common practice among ticketing services. 
* The solution is a blockchain based event ticketing protocol used by ticketing and booking companies that will make secondary market ticket prices and ticket fraud occurrences redundant 

---

# Aventus 

* The Aventus Protocol is based on blockchain technology- used in cryptocurrencies such as bitcoin- which would allow event organisers to give ticket a unique identity that is tied to its owner
* Because the tickets are based on blockchain- a linked list of records where each new one contains an encrypted version of the previous one
* The software also allows event promoters to keep an easy record of who owns the ticket, which means they can control the prices
* For the Word Cup, Aventus will join forces with another company, Blocside, and expect to work with football clubs next year on season tickets. 

---

# Blocside 

* BlocSide Sports is creating a digital platform that leverages frictionless payments, mobile ticketing, augmented reality, and Blockchain technology to improve fan engagement within professional football
* BlocSide will issue MVP Token, which is an ERC-20 compliant token that operates on the Ethereum blockchain
* ERC20 is a community defined standard that dictates a minimum set of functionality to ensure interoperability between n various tokens. 
* A fixed number of MVP Tokens (500 000 000) will be generated before the upcoming Token sale 
* 300 000 000 tokens will be sold in the token sale via a Token Sale Etheruem Smart Contract- This will allow customers to exchange Ether for tokens. (Tokens can be exchanged for fiat or digital currency only through third party exchanges and not by BlocSide or on the BlocSide Platform.)

---

# GET

* The GET Protocol offers a blockchain based smart ticketing solution that can be used by ticketing companies and event organisers to completely merge the primary and secondary ticketing market, and thus eliminating scalping
* The protocol gives complete control over the sale and trade between ticket holders from the moment the first ticket is sold until the last ticket is scanned- Every ticket is guaranteed unique, with makes ticket fraud impossible
* The protocol will offer these features while providing absolute transparency for all actors 
* These features are accomplished by introducing a smart-ticketing protocol built upon the Ethereum blockchain that will facilitate as a back-end backbone to the sale and trade of event tickets by issuing smart tickets to wallet addresses
* The owner of such a smart ticket is free to anonymously sell a ticket but can only do so within the decentralised and issuance price restricting infrastructure/rule -structure of the GET protocol
* This ensures that ticket trades are done safely and within a set price margin
* Over the counter trade or additional off-chain fee surcharges are not possible as trade is anonymous and the tickets QR code non-static
* The smart tickets QR code is dynamic and will change as a factor over time and owner of the ticket  
* This makes trading/selling the QR code outside of the protocol impossible by default
* The token, the GET, will act as the main stable value holding asset in the protocol in each event cycle
* The GET Protocol is composed entirely of smart contracts that allow for the creation and validation of events and tickets
* The issuance and sale of tickets in primary and secondary ticket markets (which can be controlled by event organisers) and the distribution of ticket sale revenue and market/event fees between the stakeholders are both monitored and executed with the smart contracts
* GUTS Tickets came to the conclusion that to truly unleash a revolution in the ticketing industry, the technology to developed should be further developed and operated form within a separate foundation so other ticketing companies will be able to make use of the GET protocol. Moreover, GUTS Tickets realised that in order to increase the pace and expanse scope, such a foundation would require sufficient resources. Hence the choice of conducting an initial coin offering for building and deploying this protocol worldwide was made. 

---

# AmicorumLive 

* Amicorum is a crowdsourced blockchain-based marketplace and peer-peer ecosystem for ticket reseal of music festivals and concerts
* Buyer’s (Fesitval/Concert enthusiasts) will be able to buy tickets (that are resold) with the AMI token (the new cryptocurrency based not Ethereum blockchain) from the sellers at 0 transaction feel and 0 processing fees.

---

# Eticket4

* Eticket4 is an international secondary ticketing platform developed by Israeli entrepreneurs in 2015
* Being an intermediary between various entities involved in the ticket re-selling process, the platform serves as a guarantor of transaction security, tickets’ validity, timely payment and delivery
* Eticket4 ticketing platform exists and its functionality is already available to ticket brokers and ticker buyers
* With the introduction of the blockchain-based functionality all token holders will contribute their efforts to its further development and receive new possibilities that would likely extend their knowledge of ticketing market and help them to take extra advantage of it
* In the fourth quarter of 2018 Eticket4 plans to introduce the blockchain-based functionality and new loyalty reward system based on ET4 crypto tokens
* The token conforms to the widely distributed standard ERC20
* The token will be prepared in cooperation with Phenom (Crypto payment system) using a smart contract written on Solidity 
* Smart contract will ensure transparency of the entire process of token distribution. Every single transaction will also be recorded into smart contracts. 

---

# Blocktix 

* The core purpose of Bloctix is to provide a decentralised event hosting and ticket distribution network. 
* Companies and individuals can buy and sell tickets through unforgeable cryptographic signatures stored on the blockchain. With this approach, the process of buying and selling tickets has been simplfied by removing the infrastructure of centralised server 
* Both parties can therefore enjoy the lowest fees and no downtime due to the decentralised nature
* The blockchain is the heart of our application and is tasked to secure a wide range of features such as payments, tickets, and the event registry
* Blocktic will be built on Ethereum because its one of the few blockchains that provides an efficient and practical toolset for smart contracts
* It will serve as the default payment gateway of our application, meaning tickets have to be purchased with the ETH cryptocurrency
* Other payment gateways such as credit cards and bank transfers will be later integrated through third parties

---

# BitTicket 

* BitTicket provides one with one wallet QR code that holds all tickets securely, no matter which ticketing provider one has bought them from 

---

# HelloSugoi 

* Their protocol can be leveraged by existing event ticketing platforms, event organisers, promoters, and artists to provide greater transparency’s scrutiny, and efficiency in the event life-cycle. 
* They have began selling tickets to the State of Digital Money on the Ethereum Blockchain 
* Their primary business is selling event tickets. They implement blockchain to enable them to provide the best value for customers 

---

# Blockets 

* They employ transaction caching as the Ethereum Blockchain is not realtime (it may take up to 10 minutes to have a transaction confirmed)- The caching system is to avoid accidental oversale
* As it is perceived, Blockchain can be difficult to deal with directly, so users are provided with a friendly wrapper around the technology- thus one can work with it, without any blockchain knowledge required. 
* Blockets SplitPayments API- is an interface that a ticket-selling service can dispatch to, to handle the actual payments of the tickets
* When a payment has been completed, the monetary amounts of tickets, that were sold will be divided as indicated in the request over the different parties
* Paying these parties will happen as soon as either a set threshold is reached or multiple days of inactivity have passed.
This means that parties will have their money a lot earlier, instead of waiting for an event to occur
