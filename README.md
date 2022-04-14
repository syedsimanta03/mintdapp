# To run the dapp Locally

nrpm run dev

Try running some of the following tasks:

```shell
npx hardhat compile
npx hardhat accounts
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help

npx hardhat run scripts/deployContract.js --network rinkeby
npx hardhat run scripts/verifyContract.js --network rinkeby
Successfully verified contract BoredApe on Etherscan.
https://rinkeby.etherscan.io/address/0x923130181b7F075cBebFc9743D6e923646FD9148#code
npx hardhat verify --network rinkeby 0xc904d4fA240d2f13D05642D850D8803642DDEB8e
```

## Console.log data
import "hardhat/console.sol";

contract Greeter {
    string private greeting;

    constructor(string memory _greeting) {
        ##console.log("Deploying a Greeter with greeting:", _greeting);##
        greeting = _greeting;
    }
