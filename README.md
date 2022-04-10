# To run the dapp Locally

nrpm run dev

Try running some of the following tasks:

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```
## Console.log data
import "hardhat/console.sol";

contract Greeter {
    string private greeting;

    constructor(string memory _greeting) {
        ##console.log("Deploying a Greeter with greeting:", _greeting);##
        greeting = _greeting;
    }
