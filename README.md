# solana-transactions
This outlines the steps to automate the process of retrieving transaction details on the Solana blockchain, specifically for Raydium liquidity operations. The provided JavaScript script utilizes the Solana Web3.js library to fetch and parse transaction details, identifying instructions related to Raydium.

This script provides a basic framework for automating the retrieval and parsing of transaction details related to Raydium on the Solana blockchain. You can extend it further to handle more complex parsing and integrate with other systems as needed.

  Brief Explanation
Setup Connection: Establishes a connection to the Solana mainnet.
Fetch Transaction: Retrieves the transaction details using getTransaction.
Inspect Instructions: Loops through the transaction's instructions to identify those related to Raydium.
Decode Data: Decodes the instruction data, where additional parsing would be necessary to extract specific details about liquidity added.
