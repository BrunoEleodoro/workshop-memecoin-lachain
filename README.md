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

- <a href="https://remix.ethereum.org" target="_blank" >Remix</a>
- <a href="https://explorer.lachain.network/" target="_blank" >Explorer LaChain Network</a>
- <a href="https://sambaswap.xyz" target="_blank" >SambaSwap</a>
- <a href="https://www.lachain.network/" target="_blank" >LaChain HomePage</a>
