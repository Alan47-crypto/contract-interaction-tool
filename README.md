# Direct Contract Interaction Tool

A powerful, browser-based tool for advanced Web3 users to interact directly with any smart contract on an EVM-compatible blockchain. This tool allows you to mint NFTs, participate in token presales, claim tokens, and call any contract function without relying on a project's front-end website.

This tool is built with pure HTML, CSS, and JavaScript, using the ethers.js library for blockchain communication and Tailwind CSS for styling.

Key Features
Direct Function Calls: Interact with any smart contract function by providing its address, ABI, and arguments.

Native Coin Payments: Send native currency (like ETH, MATIC) with payable functions for minting or buying.

ERC20 Token Payments: A built-in workflow handles the two-step approve and transfer process required for paying with tokens like USDT or USDC.

Gas Fee Estimation: Simulate transactions to get an estimated gas cost and catch potential errors before sending, saving you from failed transactions.

Wallet Integration: Connects seamlessly with MetaMask or any other browser-based Web3 wallet.

Network Agnostic: Works on any EVM-compatible network your wallet is connected to (Ethereum, Polygon, Arbitrum, Binance Smart Chain, etc.).

Self-Contained: The entire tool is a single index.html file, making it easy to host or run locally.

How to Use
Connect Wallet: Click the "Connect Wallet" button and approve the connection in MetaMask. Ensure your wallet is connected to the correct network for the transaction.

Enter Contract Details:

Minting Contract Address: The address of the smart contract you want to interact with.

Minting Contract ABI: The Application Binary Interface of the contract. For verified contracts, you can find this on a block explorer (like Etherscan) under the "Contract" tab.

Build Your Transaction:

Payment Method:

Choose "Native Coin" if you are paying with the blockchain's native currency (e.g., ETH).

Choose "ERC20 Token" if you are paying with a specific token (e.g., USDT).

Function Name: The exact name of the function you want to call (e.g., mint, claim, buyTokens).

Function Arguments: The arguments required by the function, separated by commas. Leave empty if there are none.

Fill Payment Details: Based on your chosen payment method, fill in the amount of native coin or the ERC20 token details.

Estimate Gas (Recommended):

Click the "Estimate Gas" button. This will simulate the transaction to give you an idea of the cost and check for any immediate errors.

Send Transaction:

Click "Send Transaction" (or "Approve & Mint" for ERC20) and confirm the transaction(s) in your wallet.

Monitor Logs:

Watch the "Logs & Status" box for real-time updates on your transaction's progress.

Disclaimer
This is a tool for advanced users. You are interacting directly with the blockchain. Transactions are final, irreversible, and can result in a permanent loss of funds if used incorrectly.

ALWAYS double-check the contract address.

ALWAYS verify the function names and arguments.

ALWAYS understand the transaction you are about to send.

USE AT YOUR OWN RISK. The creator of this tool is not responsible for any financial losses.
