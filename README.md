## NFT-WhiteList Dapp
Go to Contracts.sol file and copy the file and paste it in Remix Ide
![image](https://user-images.githubusercontent.com/91150257/192331136-37914dc4-d3c4-46f9-afc1-f1ec9c8e4e76.png)

Now open index.html file with any browser It will look something like this
![image](https://user-images.githubusercontent.com/91150257/192331388-773afa20-f1ce-4b83-9cbc-c1f9dc7a8d96.png)

In address input field enter your ethereum address(Note-: Do not enter address in string form)
and Click on add address(This will add your address in merkle tree) <br/>
![image](https://user-images.githubusercontent.com/91150257/192331883-900fc02f-d2da-4e47-85ac-c764be42fe54.png)


Click on Show the Merkle Root <br/>
![image](https://user-images.githubusercontent.com/91150257/192332841-277f5e7d-55d8-46e1-a42a-82089b14d215.png)



### Copy This Merkle Root 
Go into Remix Ide 
And Paste this Merkle Root In constructor field of Near Deploy Button
![image](https://user-images.githubusercontent.com/91150257/192333128-72ea5fcc-4516-4292-ab48-b69d38659096.png)


Now To mint The NFT 
you need two variables 
1. The address at which you want to mint your NFT(Paste The same address you have pasted in index file)
2. The Proof or leaf which will verify with the MERKLE ROOT(for this click on show leaf button and leaf will be pasted in console)

![image](https://user-images.githubusercontent.com/91150257/192334352-4f8175d9-7ad7-4fab-87c7-5ac08c3224db.png)

NOte -: Copy This Leaf or array and remove Any extra spaces


### How to Mint NFT

1. Paste The Address and Leaf in the given field of safe mint function 

![image](https://user-images.githubusercontent.com/91150257/192334995-5dbb11b2-7ca1-4253-90ca-ba02b2dc9454.png)

2. Click on Transact button and your NFT will be mined successfully
![image](https://user-images.githubusercontent.com/91150257/192335977-e85201e4-eb76-4580-ad30-615de05882ba.png)

3. You can also Verify your address in isValid function
