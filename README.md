###### The application of Blockchain in field of finance
### Why is blockchain trustworthy?
To a certain extent, the block chain can be understood as a replicable and shared account book. The core innovation of Bitcoin: it teaches the world how to transfer value over long distances without trusting third parties. And it relies on a consensus mechanism.
Of course, physical paper money can be transferred face to face, but before Bitcoin, we could not: transfer value to someone over long distances without the need to trust centralised third-party institutions (post offices, banks, etc.).
In this way, the infrastructure of the traditional transfer model of banks and payment systems is restructured into a peer-to-peer payment network. 
This shift is shown in the following figure：
![1](https://github.com/ansonwongphbs/www.github.com-ansonwongphbs-PHBS_BlockChain_2018/blob/master/1.png)
Bitcoin opens the door to a peer-to-peer electronic value transfer model, completely different from the current banking system, central bank and payment system. 
However, the above diagram does not explain how Bitcoin enables peer-to-peer value transfer. 
The answer is: the bitcoin system is based on "replicable, shared books". 
Each participant (full node) in the bitcoin network has a complete copy of the transaction ledger, and the magic of the system is how it makes everyone's copy consistent with that of others. 
Therefore, the correct schematic diagram should be the following figure, where each participant can obtain information from the same replicable, shared ledger.
![2](https://github.com/ansonwongphbs/www.github.com-ansonwongphbs-PHBS_BlockChain_2018/blob/master/2.png)
### Intelligent contract and Ethernet system
A smart contract program is not just a computer program that can be executed automatically: it is a system participant itself. It responds to the information it receives, it can receive and store value, and it can send information and value out. 
This program is like a person who can be trusted, can temporarily take care of the assets, and always follow the prior rules.
The following diagram is a smart contract model: a piece of code (smart contract) is deployed on a shared, copied ledger. It can maintain its own state, control its own assets and respond to external information or assets received.
![3](https://github.com/ansonwongphbs/www.github.com-ansonwongphbs-PHBS_BlockChain_2018/blob/master/3.png)
The Ethernet Square project has expanded its scope of application by drawing on the technology of bitcoin blockchain. If Bitcoin is a dedicated calculator that uses blockchain technology, Ethernet Square is a general-purpose computer that uses blockchain technology. 
To put it simply, Ether Square = blockchain + smart contract.
The biggest difference between Ether Square and Bitcoin is that it can support a more powerful scripting language (Turing's complete scripting language in technical language), allowing developers to develop arbitrary applications on it. Implement any smart contract.This is also the most powerful part of the etheric Square. 
As a platform, etherland can be compared to Apple's app store, where any developer can develop apps and sell them to users.
### Application of Intelligent contract in Financial Field
## Supply chain finance
The application scenario that block chain is recognized by the industry is focused on the field of supply chain finance in China. It is estimated that the current supply chain finance forecast is about 1.5 billion, mainly the financing of small and medium-sized enterprises.
At present, China's supply chain block chain + supply chain finance is the most widely used in accounts receivable.
Accounts receivable is very much like commercial discounted bills, except that accounts receivable are issued by core enterprises, commercial discounted bills are issued by banks, and commercial discounted bills cannot be split. 
With blockchain technology, tier 3(the suppliers of suppliers of suppliers of core enterprises, Meidi, for example) and tier 4 suppliers(the suppliers of tier 3 suppliers) who can't afford the money can raise money from relevant financial institutions with traceable accounts receivable (sourcing from core companies).
The core enterprise Meidi is the high-quality lender recognized by all the funds. Its first-class supplier according to the source shares is somewhat qualifiable. But what about tier 3, tier 4, tier N suppliers? In the existing bank credit system, these Tier 3 and Tier 4 suppliers are unqualified financiers. They cannot borrow money or can borrow money, and the interest cost is more than 15%, which is a heavy burden.
However, with the block chain technology, the primary suppliers and Sinopec (the credit market recognizes Sinopec as the core enterprise.) have generated 100 million accounts receivable, which is the source; the secondary suppliers generate 50 million of the accounts receivable to the primary suppliers. The flow of goods and other information will also be truly recorded, and can not be tampered with; the third tier to the second tier produces 10 million of the receivable. As to the fourth tier of suppliers, it may have only 400W accounts receivable traced back to the core enterprise-Sinopec. 
Because the 400W is real traceable, it can raise 300W, for instance, from the accounts receivable, and the cost is estimated at only 11%. 
In this way, the financing difficulties and expensive problems of N-tier suppliers are solved, and it is willing to pay 1% of the handling fee to the blockchain platform, credit institutions such as banks, small loans. 
In this way, it also avoids the risk of multiple pledge of an asset, greatly reducing the risk of bad debt rate.
## Contract for difference in price
Financial derivatives are the most common use of "smart contracts" and one of the easiest to implement in code. The main challenge in implementing financial contracts is that most of them need to refer to an external price publisher. For example, a very demanding application is a smart contract used to hedge against fluctuations in the price of the etheric currency (or other cryptography currency) against the dollar, but the contract needs to know the price of the etheric currency against the dollar. 
The easiest way to do this is through a "data provision" contract maintained by a particular organization, such as Nasdaq, which is designed to update the contract as needed. 
An interface is provided to enable other contracts to obtain a reply containing price information by sending a message to the contract.
When these key elements are in place, the hedge contract will look like the following：
Wait for A to enter 1000 etheric dollars.
Wait for the counterpart B to enter 1000 etheric dollars.
By querying the data providing contract, the US dollar value of 1000 etheric dollars, for example, $x, is recorded to memory. 
After 30 days, allow A or B to "reactivate" the contract to send $x worth of Ethernet coins (re-query the data to provide the contract for a new price and calculate) to A, and send the remaining Ethernet coins to B.
## Token system
The token system on the blockchain has many applications, from sub-currencies that represent assets such as dollars or gold to company stocks, individual tokens represent smart assets, and safe, unforgeable coupons, even the reward points that has nothing to do with traditional values. 
It is surprisingly easy to implement the token system in Ether Square. The key point is to understand that all currency or token systems are fundamentally a database with the following operations: subtract X units from A and add X units to B. The prerequisite is that (1) A has at least X units prior to the transaction and (2) the transaction is approved by A. To implement a token system is to implement such a logic into a contract.
## Purse for saving
Suppose Alice wants to keep her money safe, but she fears losing or being stolen by hackers. She put the Ethernet coin in a contract with Bob, as shown below, which is a bank: 
Alice can withdraw up to 1 per cent of its money a day alone. 
Bob can withdraw up to 1% of its money per day alone, but Alice can use her private key to create a transaction to cancel the withdrawal of Bob. 
Alice and Bob can withdraw funds at will together.
In general, 1% a day is enough for Alice, and if Alice wants to withdraw more money, she can contact Bob for help. If Alice's private key is stolen, she can immediately find Bob to transfer her money to a new contract. If she loses her private key, Bob can slowly bring up the money. If Bob shows malice, she can turn off his withdrawal rights.
## Insurance for the crops
One can easily create a derivatives contract based on weather conditions rather than any price index as data input. For instance, if a farmer in the Northeast of China buys a financial derivative that pays in reverse based on the rainfall in the Northeast, then if there is a drought, the farmer will automatically receive compensation money and he will be happy if there is enough rain because his crop will harvest
## Multi-signature smart contract
Bitcoin allows trading contracts based on multiple signatures. For example, if one has three of the five private keys, he could use the money 
Etherland can be more detailed. For example, if you collect four of the five private keys, you can spend all your money. If you only have three, you can spend up to 10% of your money a day. If you have only two, you can only spend 0.5% of your money every day.
