# bounty to create a NFT whitelisting contract with merkle root testing.
# tech used
- nodeJS
- merkletree.js
- Remix ide for solidity 
- openzeppelin contract 

# task explanation
the task is to create a frontend to retrive the merkle proof for a address that is whitelisted  using and use this proof generated to allow the address to mint nft in a given smartcontract.
<br>
The task will be as follows 
- create a merkle proof for any 7 ethereum address and store this in the backend .
- design a frontend to interact with this tree and when ever we query for the proof with any given address then we recieve the merkle proof
- this merkle proof is then used in the smart contract to prove that the address belongs to the merkle tree and allow its user to mint nft.
- create a basic contract that stores this merkle root and has a function mint that has a require funtion for checking the proof if a address is whitelisted or not . 
- it will also have a function that will take in the address of the user and the proof generated form the frontend and output true if we can then get the merkle root or else it returns false.

# requirements 
you will need a strong knowledge of merkle proofs and also its iimpolpementation using node

# submission
for submission provide us the link of your repo where we must find the proper implementation of the code along with the smart contract and also one example of the testing done on the smart contract along with a proper explanation of how to run the complete node porject. 


# Bounty reward 
the bounty is only for new comers and submissions form accounts that have previously not made a submission will be considered. 
<br>
the reward for this is INR 1500



