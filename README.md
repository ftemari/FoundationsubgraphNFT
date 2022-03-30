# FoundationsubgraphNFT
This proyect its simple subgraph of https://thegraph.com/ ! Its my first try to create a subgraph and modify them. 
To create this proyect i used the following guide https://fabris-86569.medium.com/construir-apis-graphql-en-ethereum-4cc6645d1360

# Description
This subgraph let you query de Etherium mainnet blockchain to bring the diferents tokens on the Foundation Contract:
- ETHscan: https://etherscan.io/token/0x3b3ee1931dc30c1957379fac9aba94d1c48a5405
- Website: https://foundation.app/ 

It has two different entities Tokens (the NFT token itself) and User (The owner of the token).

# Step by Step
To use this repository you have to follow the instructions!
- Create a TheGraph account
- Clone this repository
- Create a subgraph on the main dashboard
- Run the following command in your terminal (Requirements Node.js, Graph CLI, Access_token of your thegraph account)

```
npm install

graph build 

graph auth --product hosted-service <ACCESS_TOKEN>

graph deploy --product hosted-service <GITHUB_USER>/<SUBGRAPH NAME>
```
