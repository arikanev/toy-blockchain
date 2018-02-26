# toy-blockchain

## following commands will give genesis block properties

block.blockchain[0].data

block.blockchain[0].currentHash

block.blockchain[0].previousHash

block.blockchain[0].timestamp

block.blockchain[0].index

## make new block

block.generateNextBlock( *put whatever data you want to store here* )

## make new block and add it to the chain

block.blockchain.append(block.generateNextBlock( *put whatever data you want to store here* ))

## to validate the current chain run

block.isValidChain(block.blockchain)
