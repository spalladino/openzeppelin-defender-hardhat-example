# openzeppelin-defender-hardhat-example

Example usage of the @openzeppelin/defender-hardhat plugin for proposing a contract upgrade via Defender.

## Usage

- Clone the repo and install dependencies
- Create a Defender account and create a Team API Key
- Set up a `.env` file with the values listed below
- Run with `yarn run main`

## Environment file

Create in `.env` in the project root.

```bash
API_KEY=       # Defender team API key with capability to create admin proposals
API_SECRET=    # Corresponding API secret
INFURA_TOKEN=  # Token for connecting to Infura
PRIVATE_KEY=   # Private key with funds on rinkeby for deploying the implementation contracts
OWNER_ADDRESS= # Address of the upgrades owner (recommended to be a Gnosis Safe or Gnosis MultisigWallet)
```
