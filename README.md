# AddressStorage.sol
AddressStorage.sol3
pragma solidity ^0.8.20;

contract AddressStorage {
    address public user;

    function setAddress(address _addr) public {
        user = _addr;
    }
}
Add require checks
