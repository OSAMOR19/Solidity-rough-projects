# Solidity-rough-projects
this contract is used to reveal the standard units of ethereum
//SPDX-Licence-identifier: MIT

pragma solidity ^0.8.0;

contract EtherUnits {
        uint public oneWei = 1 wei;
        uint public oneEther = 1 ether;

        function testonewei () public pure returns (bool) {
            return 1 wei ==1;
        }

        function testoneEther () public pure returns (bool) {
            return 1 ether == 1*10^18 wei;
        }

}



