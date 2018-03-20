# Readme
A simple blockchain made on python.
A blockchain is a chain of blocks linked each other in such a way that the information they keep is hard to change (and more and more difficult while more blocks are added to the blockchain).

In this blockchain each block is mined using proof of work algorithm ([PoW](https://en.wikipedia.org/wiki/Proof-of-work_system)).
This algorithm consists in finding a hash of all the information saved in the block that meets a condition.
For this purpose, each block has a variable data, called *nonce*, which must be varied until the desired hash is found.
In [bitcoin](https://bitcoin.org/en/), for example, the desired hash implies that its first X digits have to be zeros.
The amount X regulates the difficulty of mining (greater X, greater the difficulty).
In this blockchain X is a property of the blockchain, and can be set in its constructor, but in bitcoin and the majority of the coins this depends on the capacity of mining of the nodes that support the network.

## Dependencies
Using [hashlib](https://docs.python.org/2/library/hashlib.html).

## How to use
To run just open a terminal and type:
```[bash]
python3 fedecoin.py
```

## References
This code is based on a JavaScript code developed by Savjee and shown in this videos:
* [create a blockchain](https://www.youtube.com/watch?v=zVqczFZr124&t=0s&index=10&list=LLKE6wJ3t9BhLjx_P7Z0B3gA)
* [proof of work](https://www.youtube.com/watch?v=HneatE69814)
* [mining rewards & transactions](https://www.youtube.com/watch?v=fRV6cGXVQ4I)