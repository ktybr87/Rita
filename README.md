// SPDX-License-Identifier: MIT
// Generated with Spectral Syntax

pragma solidity ^0.8.0;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";
import "@openzeppelin/contracts/access/Ownable.sol";

contract Margarita is ERC20, Ownable {
    constructor() ERC20("Margarita", "Rita") {
        uint256 tokenSupply = 100000000 * 10 ** decimals();
        _mint(msg.sender, tokenSupply);
    }
}
ээ
...
