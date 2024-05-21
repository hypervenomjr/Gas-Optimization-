# Getting Started

    curl -L https://foundry.paradigm.xyz | bash
    foundryup
    brew install libusb

# Gas Optimization

| Title                            | Guide                              | Contract                            |
| :------------------------------- | :--------------------------------- | :---------------------------------- |
| Arithmetic & Bitwise Operators   | [Guide](docs/Arithmetic.md)        | [Contract](src/Arithmetic.sol)      |
| Public vs External               | [Guide](docs/PublicExternal.md)    | [Contract](src/PublicExternal.sol)  |
| Default Initialization (x)       | [Guide](docs/DefaultInit.md)       | [Contract](src/DefaultInit.sol)     | 
| Revert Strings                   | [Guide](docs/RevertString.md)      | [Contract](src/RevertString.sol)    |  
| Redundant Checks                 | [Guide](docs/RedundantCheck.md)    | [Contract](src/RedundantCheck.sol)  |
| Nested If Statements             | [Guide](docs/NestedIf.md)          | [Contract](src/NestedIf.sol)        |  
| State Variable vs Local Variable | [Guide](docs/Array.md)             | [Contract](src/ArrayLength.sol)     |    
| Packing Variables                | [Guide](docs/PackVariables.md)     | [Contract](src/PackVariables.sol)   |  
| Data Types                       | [Guide](docs/DataType.md)          | [Contract](src/DataType.sol)        |
| Addition                         | [Guide](docs/Addition.md)          | [Contract](src/Addition.sol)        |    
| Garbage Collection               | [Guide](docs/GarbageCollection.md) | [Contract](src/GC.sol)              | 
| Swap                             | [Guide](docs/Swap.md)              | [Contract](src/Swap.sol)            | 
| Call Data vs Memory              | [Guide](docs/CDMem.md)             | [Contract](src/CDMem.sol)           |    
| Immutable                        | [Guide](docs/Immutable.md)         | [Contract](src/Immutable.sol)       |    
| Solidity Version                 | [Guide](docs/SolidityVersion.md)   |                                     |     
| Unsigned Integer Comparision     | [Guide](docs/CompareZero.md)       | [Contract](src/CompareZero.sol)     |   
| Boolean                          | [Guide](docs/Boolean.md)           |                                     |  
| Custom Errors                    | [Guide](docs/CustomError.md)       | [Contract](src/CustomError.sol)     |   
| Optimization                     | [Guide](docs/Optimization.md)      |                                     |    
| Use of Library                   | [Guide](docs/Library.md)           |                                     |                                     
| String vs Bytes32                | [Guide](docs/StringBytes.md)       | [Contract](src/StringBytes.sol)     |   
| Multiple Require                 | [Guide](docs/MultipleRequire.md)   | [Contract](src/MultipleRequire.sol) |  
| Loop Post Condition              | [Guide](docs/LoopPost.md)          | [Contract](src/LoopPost.sol)        |   
| Dead Code                        | [Guide](docs/DeadCode.md)          |                                     |                                     
| Short Circuiting                 | [Guide](docs/ShortCircuiting.md)   |                                     |                                     

# References

1. https://betterprogramming.pub/how-to-write-smart-contracts-that-optimize-gas-spent-on-ethereum-30b5e9c5db85?gi=227bef2ca134
2. https://mudit.blog/solidity-gas-optimization-tips/
3. https://blog.polymath.network/solidity-tips-and-tricks-to-save-gas-and-reduce-bytecode-size-c44580b218e6
4. https://gist.github.com/hrkrshnn/ee8fabd532058307229d65dcd5836ddc
5. https://medium.com/coinmonks/8-ways-of-reducing-the-gas-consumption-of-your-smart-contracts-9a506b339c0a
6. https://ethereum.stackexchange.com/questions/28813/how-to-write-an-optimized-gas-cost-smart-contract
7. https://forum.openzeppelin.com/t/a-collection-of-gas-optimisation-tricks/19966
8. https://medium.com/coinmonks/8-ways-of-reducing-the-gas-consumption-of-your-smart-contracts-9a506b339c0a
