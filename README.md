# Time-Locked Pension Fund

A simple Solidity contract for a time-locked pension fund. The core contract source is [pension.sol](pension.sol).

**What this repo contains:**
- `pension.sol` — the Solidity contract implementing the time-locked pension fund.

**Quick overview**
- Purpose: allow funds to be locked and released to beneficiaries after a specified unlock time.

**Remix (online IDE)**
- This contract was created and tested using the Remix IDE (https://remix.ethereum.org).
- To open and run the contract in Remix:

```bash
# 1. Open https://remix.ethereum.org in your browser
# 2. In the File Explorer, create a new file and paste the contents of `pension.sol` (or drag the file into Remix)
# 3. In the Solidity compiler tab, select a compiler version compatible with the contract and click 'Compile'
# 4. In the Deploy & Run tab, choose an environment (e.g., JavaScript VM, Injected Web3) and deploy the contract
# 5. Interact with the deployed contract using the Remix UI
```

Notes:
- When using injected providers (e.g., MetaMask), ensure the selected account/network matches your testnet/mainnet target.
- For quick iterative testing, `JavaScript VM` is the fastest option in Remix.
