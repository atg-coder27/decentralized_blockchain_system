# Decentralised-transaction-network
This is an example of a basic distributed decentralized ledger which enables the users connected in the network as node to perform transactions with each other.

# Installations 
Python 
requests 
flask 
crypto

# Instructions
In order to simulate an actual network, Three nodes have been created on different ports 5001, 5002, 5003.\n
To run the network run each of the nodes simultaneously.\n
Make sure to add the nodes of the netowrk using the add_nodes fucntion created for each of the node.\n
Feel free to add more nodes into the network.\n
Mine your first block using any of the added nodes using the mine_block function.\n
Once mined, Get all the other nodes to consensus using the replace_chain function for the remaining nodes.\n 
Send your first transaction using the add_transaction function.\n
Once the transactions have been made mine the block again and get the other nodes to consensus.\n
Here the recievers have been called by names but given a real life situation, we will be issuing separate public and private keys to ensure security.\n
