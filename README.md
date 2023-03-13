# simple_blockchain
An example of a simple blockchain in Python.
In this example, we are creating a Block class, which represents a single block in our blockchain. Each block contains an index, data, the hash of the previous block, and its own hash, which is calculated by combining the block's data and its hash of the previous block and hashing using the SHA-256 algorithm.

We then create a Blockchain class, which is a chain of blocks. First, we create a genesis block, which has an index of 0 and contains arbitrary data. Then we add several blocks with arbitrary data, each new block refers to the hash of the previous block. Finally, we check if our block chain is valid using the is_chain_valid() method, which checks that the hashes of each block match their content, and that links to previous blocks are also valid.

This example is only a basic example that can be extended and extended to suit your needs.
