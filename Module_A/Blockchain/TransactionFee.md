## What Are Bitcoin Transaction Fees?
- Mathematically, transaction fees are the difference between the amount of bitcoin sent and the amount received. 
- Conceptually, transaction fees are a reflection of the speed with which a user wants their transaction validated on the blockchain. 
- When a miner validates a new block in the blockchain, they also validate all of the transactions within the block.



## How Are Transaction Fees Determined?
- Transaction fees are based on the data volume of a transaction and the congestion of the network. A block can contain a maximum of 4 MB of data, so there is a limit to how many transactions can be processed in one block. A larger transaction will take up more block data. Thus, larger transactions typically pay fees on a per-byte basis

- If you are sending a transaction with the help of a Bitcoin wallet, the wallet will usually display an option for you to select your fee rate. This fee rate will be calculated in satoshis per unit of data your transaction will consume on the blockchain, abbreviated as sats/vByte. The total fee paid by your transaction will then be this rate multiplied by the size of your transaction.

- If you wish to have your transaction confirmed immediately, your optimal fee rate may vary significantly. However, if you do not mind waiting, paying 2 sats/vByte will usually allow your transaction to be confirmed within a day or a week.

## Transaction Speed
- Transaction fees also reflect the speed with which the user wants to have the transaction validated. When a user initiates a transaction, it goes into the mempool. Upon validation, it is included in the block. Miners choose which transactions to validate and include in the block. When there is a backlog of transactions waiting to be validated, it creates an incentive for miners to process transactions with higher fee rates first. Most miners target transactions with high fee to byte ratios. When network transactions begin to reduce, transaction fees will fall.