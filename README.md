# Assignment-1-Extend-the-Mini-Blockchain
Screenshots of Output:
<img width="1301" height="826" alt="1" src="https://github.com/user-attachments/assets/ddd5a9ea-58f5-43c2-b2ff-164526ffd0af" />
<img width="1151" height="748" alt="Capture" src="https://github.com/user-attachments/assets/d959d297-44b1-427c-b140-5e0861e08c4b" />
To run the code, open the terminal in Virtual Box, Ubuntu and run, "node blockchain.js" this will then execute the code in blockchain.js.  

Reflection: 

What did you learn about hashing & immutability?
  I learned that hashing will create unique fingerprints for the blocks of data, if anything changes about the block then the has will completely change.
  I also learned that since the blocks depend each other, if one block is tampered with then the chain's integrity is violated since they depend on the hash
  of the previous ones. 
Why does Proof-of-Work make blockchains secure?
  Proof-of-Work makes blockchains secure because it implements a challenge for attackers. This makes it harder for attackers to alter past blocks, 
  due to the difficulty criteria. If they wanted to change the block then they would have to re-mine all subsequent blocks, which is very intensive
  and almost impossible due to the computational power needed.
What surprised you while coding this?
  I was surprised at how simple but effective the core ideas of blockchain are. Just linking blocks with hashes and adding a mining challenge creates strong security and tamper resistance. This randomness shows how hard real mining is.
