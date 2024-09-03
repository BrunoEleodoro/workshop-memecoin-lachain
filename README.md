## Workshop Memecoin: criando sua primeira memecoin na rede da LaChain

## Contratos

Memecoin.sol
```
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";

contract Memecoin is ERC20 {
    constructor(uint256 initialSupply) ERC20("Memecoin", "MEME") {
        _mint(msg.sender, initialSupply);
    }
}
```

## Links Rapidos

- https://remix.ethereum.org
- https://explorer.lachain.network/
- https://sambaswap.xyz
- https://www.lachain.network/
