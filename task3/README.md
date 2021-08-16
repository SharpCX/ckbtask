- 1. A screenshot of the console output immediately after you have successfully issued a smart contract call.
![](task3.png)
- 2. The transaction hash from the console output (in text format).
0xe29d2fb53826b12ed062ca3bdbb526b77ea11e8a98ffb26980cfdc5917aa3c33
- 3. The contract address that you called (in text format).
0x09b240580aFda07126928216a92fEc3Da454abAE
- 4. The ABI for contract you made a call on (in text format).
``` js
[
    {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "x",
          "type": "uint256"
        }
      ],
      "name": "set",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "get",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
  ]
  ```