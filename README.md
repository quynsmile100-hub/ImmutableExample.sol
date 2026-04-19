# ImmutableExample.sol
ImmutableExample.sol
pragma solidity ^0.8.20;
contract ImmutableExample {
    uint public immutable value;

    constructor(uint _v){
        value = _v;
    }
}
