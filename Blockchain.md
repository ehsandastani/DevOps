# Blockchain

First, we should know this is just a data structure like the others! It is not a separate layer in the network that we have to merge them! :pinched_fingers: <br>
<p align="justify">
With blockchain technology, we can create an environment in which nodes that do not trust one another can share data they can trust. The idea is based on several concepts that are simple to consider but difficult to put into practice. First, data is logically presented as a ledger. The data isn't really stored that way; you can just think of it as a ledger.
</p>

:bulb: Let's have an abstraction about BC (blockchain) first:
* A ledger is a way of recording data as transactions occur.
* You can only add data to a ledger. You cannot change anything after you've added it. So, the only two operations you can perform on this ledger are <b>"add"</b> and <b>"read"</b>.
* Data is added to this ledger in blocks. blocks are collections of transactions, each with an owner's address.
* Addresses are the unique IDs of accounts in our ledger system.
* When there are enough transactions to make a new block, some of the blockchain participants begin the process of adding a new block to the ledger.
* Each new block is linked to the previous block, making a chain.
* Then, The entire set of blocks, or the entire blockchain, is shared with other participants that are called nodes.
* These nodes communicate with one another and each store an exact copy of the blockchain.
* <p align="justify">Before any new block is added to the blockchain, a majority of nodes must agree that the new block is valid. All nodes agree to accept the majority decision. That's how the blockchain stays in sync.</p>
* Nodes essentially vote on all new blocks. Different blockchains use different voting methods (e.g. solving very hard mathematical puzzles).
* Each node periodically scans the blockchain to ensure that nothing has changed. This is how nodes can be sure that the blockchain is the same across the entire network.

<p align="justify">
Putting it all together, a blockchain makes it possible to share a set of data with many nodes that you don't trust. You can trust the democracy of the network, though. <b>As long as you can trust that more than half of the nodes on the blockchain network are going to be honest, you can trust the blockchain.</b>
</p>

### :point_right: Smart Contract
<p align="justify">
The last big advantage to blockchain is that you can put rules of operation in blocks on the BC as well. These rules are called "<em>smart contract</em>". A smart contract is just a program that lives in a blockchain block and governs how data is added to the BC. Because all blockchain data is immutable <a href="#footnote-1">[Note1]</a>, even the smart contract code is immune from changes.
</p>

<p align="justify">
  For example, suppose you want to buy a car. You have enough digital currency in your blockchain account to buy the car, and the car owner has the car’s title stored in the blockchain. You can offer to buy the car and if the seller accepts your offer, a smart contract handles the transaction.
The smart contract would verify that the title is owned by the seller and that you have enough money in your account to 
make the purchase. If those two requirements are met, the smart contract will
transfer the sales amount into the seller’s account and transfer the title to your
account. Without any middleman, you have purchased a car and paid for it without
carrying a wad of cash around.
</p>


Of course, you really purchased a title to a car. Blockchain handles digital assets You still have to physically get the keys and the car from the seller! :grin:

<p id="footnote-1" align="justify">[Note 1]: Immutability  isn’t  actually  a  blockchain  guarantee.  You  can  change
data in any block,  even after other blocks are added to the blockchain.
However, as soon as you change a block, that block and all subsequent blocks fail integrity checks  and  your  node  is  out  of  sync. 
 Instead  of  saying  that  the  blockchain  is 
immutable, it is more accurate to say that any changes (mutations) to the blockchain
are easily and immediately detected. </p>

## :point_right: Ethereum
<p align="justify">
Ethereum wasn’t created just to exchange cryptocurrency. In fact, it was designed
from  the  beginning  to  be  different.  The  core  features  of  Ethereum  are  the 
smart  contract  and  ether. 
<b><em>Ether</em></b>  is  the  native  cryptocurrency  that  Ethereum
supports,  although  you  can  create  your  own  tokens  to  exchange  value  in  many 
other  forms. Smart  contracts  provide  an  execution  environment  that  ensures 
integrity across all nodes. Any code that executes on one node executes the same 
way  on  all  nodes.  This  guarantee  makes  it  possible  to  deploy  a  wide  range  of applications across untrusted environments.
</p>

### :point_right: Ethereum's Consensus
<p align="justify">
 Each node in Ethereum gets an equal vote. Every time nodes get a new block to add to the blockchain, they validate the block and its
 transactions, and then vote whether to accept or reject the block. If several different
blocks are submitted by different nodes, only one of the blocks can receive votes 
from a majority. The block that gets more than half of the network node’s votes 
gets to join the blockchain as its newest block.
</p>

<p align="justify">
One of the first problems is to determine when a new block is ready for the
BC. When too many conflicting blocks are submitted, the voting process slows 
down. Ethereum makes it hard to add new blocks to keep the number of new block 
collisions  low  and  to  make  voting  faster. 
Ethereum  uses  a  consensus  protocol called 
<em>Proof of Work  (PoW)</em>, which  sets  the  rules  for  validating  and  adding  new 
blocks. PoW makes add blocks to the blockchain difficult but profitable.
</p>

<p align="justify">

</p>
