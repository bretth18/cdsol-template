# cdsol-template

template repository for solidity development with forge.

## Getting Started

```
mkdir reponamehere
cd reponamehere
forge init --template https://github.com/bretth18/cdsol-template
yarn install
forge build
forge test
```

## Features

### Testing Utilities

Includes:

- `Hevm.sol`
- `DSTestPlus.sol`
- `DSInvariantTest.sol`
- `Console.sol`
- `Utilities.sol`


### Preinstalled dependencies

- `ds-test`
- `solmate`
- `open-zeppelin/contracts`

### Linting

Pre-configured `solhint` and `prettier-plugin-solidity`. Can be run by

```bash
$ yarn format
$ yarn format:fix
$ yarn lint
$ yarn lint:fix
```

### CI

Automatically run linting and tests on pull requests.

### Default Configuration

Including `.gitignore`, `.vscode`, `remappings.txt`


