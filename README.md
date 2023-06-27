# On-Chain Art Database

## What is on-chain art?
On-Chain Art is a pioneering initiative to document on-chain projects.

Most NFTs store their data off-chain (meaning off the "blockchain") due to the high cost of storing data on the blockchain itself. These NFTs store an identifier that points back to the description of the artwork and the corresponding visuals. However, if the server or the database to which the identifier points goes down, the art also disappears. This vulnerability contradicts the ethos of immutability that a distributed ledger should uphold.

To address this issue, a new paradigm has emerged among smart contract developers and artists: on-chain art. The term "on-chain" refers to the practice of storing code, artwork, and/or metadata directly on the blockchain, ensuring permanence and immutability. As long as the Ethereum network exists, the data will be permanently stored on it. This reliance on the Ethereum Virtual Machine presents numerous constraints, which in turn stimulate creativity.

A list of on-chain projects live on the mainnet has been documented by tens of people on the [0xchain.art](0xchain.art) website.

## Data

```
{
    "id": "473",
    "contractAddress": "0x55081b12a3a73236c75bcdd49db04a85cc1496b7",
    "name": "Tiny Explorers",
    "rating": "3",
    "jsonData": {
        "name": "Tiny Explorers",
        "slug": "tiny-explorers",
        "assets": [
            "https://openseauserdata.com/files/bacbed73fb390385a1ddeeff3a1620e9.svg",
            "https://openseauserdata.com/files/bc1f1b582701a6a4c53199081c264f87.svg",
            "https://openseauserdata.com/files/a05a39930b009ee1dc0f45371ebeb0b5.svg",
            "https://openseauserdata.com/files/e57b215320c2f3cfe860ffed4475fd3b.svg"
        ],
        "rating": 3,
        "ensName": "tinykingdoms.eth",
        "license": "CC0",
        "dateAdded": 1658401447,
        "createdDate": 1652609005,
        "description": "Tiny Explorers is a collection of fully on-chain explorers. \n\nAs Tiny Kingdoms vie for control of the limited resources, a few explorers have found a way to make a living by exploring the unknown. These brave souls venture into the abyss, searching for new lands and resources to bring back to their respective kingdoms.\n\nCC0 and on-chain",
        "websiteLink": "http://www.tinyexplorers.xyz",
        "contractLink": "https://etherscan.io/address/0x55081b12a3a73236c75bcdd49db04a85cc1496b7#code",
        "collectionLink": "https://opensea.io/collection/tiny-explorers",
        "creatorAddress": "0x5c11cc01a141c17ef24218ab10762d2f01562bad",
        "contractAddress": "0x55081b12a3a73236c75bcdd49db04a85cc1496b7"
    }
}

```


# Data Structure

1. **ID**: "473" - This is a unique identifier for this entry in the database.
2. **Contract Address**: "0x55081b12a3a73236c75bcdd49db04a85cc1496b7" - This is the Ethereum address of the smart contract associated with the "Tiny Explorers" on-chain art project.
3. **Name**: "Tiny Explorers" - This is the name of the on-chain art project.
4. **Rating**: "3" - This is the rating assigned to the project based on the rating system explained earlier.
5. **JSON Data**: This is a JSON object containing additional information about the "Tiny Explorers" project:
   - **name**: "Tiny Explorers" - The name of the project, same as the "Name" field.
   - **slug**: "tiny-explorers" - A URL-friendly version of the name.
   - **assets**: This is an array of URLs pointing to the visual assets associated with the project.
   - **rating**: "3" - The rating of the project, same as the "Rating" field.
   - **ensName**: "tinykingdoms.eth" - The Ethereum Name Service (ENS) name associated with the project.
   - **license**: "CC0" - The license associated with the project.
   - **dateAdded**: "1658401447" - The Unix timestamp when the project was added to the database.
   - **createdDate**: "1652609005" - The Unix timestamp when the project was created.
   - **description**: This is a description of the project.
   - **websiteLink**: "http://www.tinyexplorers.xyz" - A link to the project's website.
   - **contractLink**: "https://etherscan.io/address/0x55081b12a3a73236c75bcdd49db04a85cc1496b7#code" - A link to the project's smart contract on Etherscan.
   - **collectionLink**: "https://opensea.io/collection/tiny-explorers/" - A link to the project's collection on LooksRare.
   - **creatorAddress**: "0x5c11cc01a141c17ef24218ab10762d2f01562bad" - The Ethereum address of the project's creator.
   - **contractAddress**: "0x55081b12a3a73236c75bcdd49db04a85cc1496b7" - The Ethereum address of the project's smart contract, same as the "Contract Address" field.
   
   This specific entry represents the "Tiny Explorers" project, which is a collection of fully on-chain explorers. 


## Data Access
The data for the on-chain art projects is stored in two files:

- [data.csv](https://github.com/onchain-art/onchain-art-db/blob/main/data/data.csv): CSV format
- [data.md](https://github.com/onchain-art/onchain-art-db/blob/main/data/data.md): md format

Please note that both files contain the same data, just in different formats. Choose the one that best fits your needs.

## Ratings

The rating system on this site is taken from Dom Hoffman’s [tweet](https://twitter.com/dhof/status/1410060181849919489) and manually evaluated by [Emre](https://twitter.com/emrecolako).

## Feedback

If you have any questions / comments please submit and issue or message me on [twitter](https://twitter.com/emrecolako).

