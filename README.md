# Chord-P2P-Architecture
Python implementation of CHORD P2P protocol with HeartBeat for finding fault tolerance

Run command:  
```
python Node.py
```
It asks for IP,Port and N(parameter in CHORD Architecture). It opens a terminal(command line interface) for a node.
You can now run different commands:
1. ```print``` prints info about current node
2. ```create_ring``` creates main Ring
3. ```join <current_ip> <to_join_ip>``` joins to P2P Architecture given ip of already existing node in Ring
4. ```find``` finds next node in P2P Architecture
5. ```add_key <key>``` add key in the DHT
6. ```find_key <key>``` find node storing value for key
7. ```print_table``` prints whole key table
8. ```close``` removes node from P2P Architecture gracefully
