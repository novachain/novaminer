# novaminer

Evolved from https://github.com/JohnnyFFM/blagominer

## What is Valve Proof of Capacity (vPoc)?
Valve Proof of Capacity vPoc is, in general, a mechanism to ensure that a party has dedicated a particular (significant) amount of storage space towards a specific goal. NOVA uses vPoc in the process of transaction verification for the validation and generation of blocks. Here, miners use a given amount of disk space to fill with plots. The more disk space is plotted, the higher the chances to generate (win) a block. PoC is thus in direct contrast to other consensus algorithms like Proof of Work (PoW) and Proof of Stake (PoS) where block generators need to proof the performance of some difficult computations or the ownership of a significant amount of currency, respectively.

## What's the difference between PoC and vPoC
Valve-Proof-of-Capacity(vPoC) is an improvement based on Proof-of-Capacity(POC).
POC algorithm can provide effective capacity to multiple blockchains at the same time, This will lead to serious cheating in computing power of some blockchains. This is often unfair to participants .
vPoC adopts the irreversible cycle algorithm to eliminate the cheating capacity of blockchain. POC plotter cannot provide any effective capacity to vPoC chain. This creates a more equitable environment for all participants. 

## Advtantages of vPoc
In contrast to PoW, vPoc is considered to be more eco-friendly. While PoW requires expensive computations each time a block is generated, vPoc puts most of the required computational costs up-front in the plotting process. Reading the plots in order to proof the designated disk space investment is much cheaper. Additionaly, users can mine using their existing hardware, instead of having to to invest in special purpose hardware like e.g. ASICS for Bitcoin mining.In contrast to PoS, vPoc allows a fairer distribution of coins as they are generated over time and assigned to active miners. In a PoS coin like NXT, the number of coins is fixed from the beginning and has to be distributed somehow initially. This leads to an unequal distribution of wealth to a few selected early adopters, e.g. via airdrops.
