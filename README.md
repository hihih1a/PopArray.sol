# PopArray.sol
PopArray.sol
pragma solidity ^0.8.20;
contract PopArray {
    uint[] public arr;

    function push(uint x) public {
        arr.push(x);
    }

    function pop() public {
        arr.pop();
    }
}
