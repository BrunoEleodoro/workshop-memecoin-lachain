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

- <a target="_blank" href="https://remix.ethereum.org">Remix</a>
- <a target="_blank" href="https://explorer.lachain.network/">Explorer LaChain Network</a>
- <a target="_blank" href="https://sambaswap.xyz">SambaSwap</a>
- <a target="_blank" href="https://www.lachain.network/">LaChain HomePage</a>
