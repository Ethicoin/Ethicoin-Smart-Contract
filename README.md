Ethicoin
Ethicoin is a BEP-20 token with advanced features like dividend distribution and liquidity management. Below you'll find essential information about its features, functionalities, and usage.

Overview
Name: Ethicoin
Symbol: ETHIC+
Decimals: 9
Total Supply: 1,000,000,000,000 ETHIC+

Key Features
Dividend Distribution: Ethicoin distributes dividends in RWRD (Reward Token) to holders. Dividends are processed automatically.
Anti-Whale Mechanisms: Max transaction and wallet limits to prevent excessive holdings and transactions.
Fee Structure:
Liquidity Fee: 2%
Reflection Fee: 5%
Marketing Fee: 5%
Development Fee: 1%

Blacklist: Option to blacklist addresses to prevent malicious activity.
Contract Interfaces
IBEP20: Standard BEP-20 functions (e.g., transfer, approve, balanceOf).
IDividendDistributor: Handles dividend distribution and settings.
IDEXRouter & IDEXFactory: Interfaces for interacting with decentralized exchanges.

Setup & Usage
Deploying the Contract: Deploy the contract to the Binance Smart Chain network.
Interacting with the Contract: Use standard BEP-20 functions for transactions. To interact with the dividend features, call functions like setShare or deposit.

Functions
Dividend Distribution: Call deposit to add dividends to the pool and process to distribute them to holders.
Manage Fees: Use setFees to adjust liquidity, reflection, marketing, and development fees.
Airdrops: Use multiTransfer or multiTransfer_fixed to distribute tokens to multiple addresses.

Security & Governance
Ownership: Contract owner can manage key functionalities like trading status, fees, and blacklisting.
Audits: Ensure the contract is audited and verified for security.

Contact & Support
Website: https://www.ethicoin.org
Support: Contact us via our website for any queries or support.
