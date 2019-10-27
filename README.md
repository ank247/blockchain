# Blockchain

Neural Network based Blockchain

Interview:
1. Develop consensus using Web3 for dumping or adding blocks.
2. Questions will be asked based on the protocols/algos used for the successful of the following consensus.
3. Questions using those protocols will be asked.

links[Complete Block explanation]: https://en.bitcoin.it/wiki/Dump_format#CBlock

BLOCKS



# bitcoin

1.Transactions:

Challenges:

    1. Verification of Double-Spend(Multiple signing of the same block) check on Transactions
    
Solution: 

         1. The Transactions should use third-party for verification.
         2. The majority of nodes agree with the received transaction is first by the following Payee. 

2.Timestamp Server:

Solution for Double-Spend:
    
    1. The timestamp attached indicates that the Transaction would have been signed at some earlier timestamp.
    
3.Proof-of-Work:

Target:
    
    1. Increase difficulty for Proof-of-Work so that the transactions stored in blocks by each node could be 
       allowed to passby other participating nodes.

Solution for:
 
    1. Determining representation in majority decision making.
  
Challenges:
    
    1.If 1-IP 1-Vote given for majority, multiple IPs comes into picture by a single client.
    2.The compensation in hardware speed and varying in interest of speed of blocks for nodes 
      leads to difficulty of Proof-of-Work(PoW).  
    
Solution:[Dominancy][Super-admin concept creation]

    1. 1-CPU-1-Vote: CPU power allocation to the one-honest node reduces capability of adversary nodes by CPU-power.
    2. For decremention of PoW for hardware speed of honest node, there is fixing of average nos. of blocks per hour. 

4. Network Setup:
   
Principles:
       
    1. Longest chain of blocks are acceptable.
    2. #Creation:The node finding best and soonest Proof-of-Work, i.e, honest node, transfers block 
       with hashes to every node. The nodes accept it only with no blocks are spent(doubly signed).
    3. #Acceptance:The other node on getting PoW for the block passing through it, add an extra block 
       to the chain with hash generated using hashes from the previous block w.r.t it.
    4. #Rejection:If any block in the chain found not validating PoW, the complete chain is rejected.
    5. #Tie:Throughout the process, there could be more than a chain running throughout the nodes. If
       2nd time PoW is found,the 'Tie' among multiple break and it follows longer chain out of existing.
    6. The new blockchain must not be passing by all the nodes again. The nodes not getting the chain
       raise request for the chain.
    
5. Incentive:
6. Reclaiming Disk Spaces:
7. Simplified Payment Verification:
8. Combining and Splitting Values:
9. Privacy:
10.Calculation:

# Ideation:
1. Gold Miners(sooner PoW generator): Paid with incentives from needing nodes for transaction. Each nodes paid 
   for less than or equal to ether transacted valued product with Gold Miners with extra bonus. The minter will
   be having high CPU-power node to earn more gold coin.
   
2.

    
