# NFT Srb - A Serbian NFT Marketplace  
### [Full Demo](https://www.youtube.com/watch?v=wW_Nj_gqfDo) <br>  
![Gif demo](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcGIxNHhlM3NlOWR4b3c5eDE4YWlmNzVhem84cXZ0bGVtMm15ajFteiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/qWmuf3C4gC16is6R7X/giphy.gif)  
<br>  
A NFT marketplace deployed on an Ethereum testnet (Ropsten - RIP in peace legend).  
This app has been created as part of my final thesis for my bachelor's degree. It enables the user to:  
- Login with his Metamask wallet;  
- Mint their own NFTs;  
- Set their NFTs for sale on the marketplace;  
- Search for other users' NFTs;  
- Buy NFTs.

### <b>[Backend:](https://github.com/MilanBrkic/nft-srb-be)</b>  
- Written in Node.js and TypeScript;  
- MongoDb for storing off-chain data;  
- Ethers.js was used as a package for listening to blockchain events;  
- The app has been deployed on Heroku, utill they killed the free tier (RIP in peace legend);  
- JWT auth.

  
### <b>[Smart Contract:](https://github.com/MilanBrkic/nft-smart-contract)</b>  
- Solidity;  
- Inherited ERC721URIStorage with some modifications;  
- Used Hardhat for development;  
- Deployed with Remix on Ropsten.

  
### <b>[Frontend:](https://github.com/MilanBrkic/nft-srb-fe)</b>  
- Ethers.js for calling smart contact methods;  
- NFTs pictures were saved on IPFS with NFT.storage and Google Drive for faster performance;  
- React;  
- Deployed on Github Pages (ik lame).

## App architecure
![App architecture](https://github.com/MilanBrkic/nft-srb/blob/main/NftSrb-arch.png)

Fun fact: this app has been developed and deployed in the middle of a Ropsten migration to Proof of Stake (I had no idea of it at the time). Luckily, everything worked fine.
