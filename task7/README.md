### 1. Screenshots or video of your application running on Godwoken.
![](t70.png)
![](t71.png)
![](t72.png)


### 2. Link to the GitHub repository with your application which has been ported to Godwoken. This must be a different application than the one covered in this guide.

https://github.com/SharpCX/CkbWeightRecorder


### 3. If you deployed any smart contracts as part of this tutorial, please provide the transaction hash of the deployment transaction, the deployed contract address, and the ABI of the deployed smart contract. (Provide all in text format.)

- Deployed contract address: 0x9D1E1fb351d9b94B6429d4cB315374142A8E3D52
- Deploy transaction hash: 0xceafee89e7e4fe2cbab7318f1e8c6ee1b798c8d0561e6787c56fc16a01f3406f

``` json
[
    {
      "inputs": [],
      "stateMutability": "nonpayable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "string",
          "name": "time_string",
          "type": "string"
        },
        {
          "internalType": "uint8",
          "name": "weight",
          "type": "uint8"
        }
      ],
      "name": "record",
      "outputs": [
        {
          "internalType": "bool",
          "name": "",
          "type": "bool"
        }
      ],
      "stateMutability": "nonpayable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "getRecords",
      "outputs": [
        {
          "internalType": "string[]",
          "name": "",
          "type": "string[]"
        },
        {
          "internalType": "uint8[]",
          "name": "",
          "type": "uint8[]"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "address",
          "name": "addr",
          "type": "address"
        }
      ],
      "name": "getOneUserRecords",
      "outputs": [
        {
          "internalType": "string[]",
          "name": "",
          "type": "string[]"
        },
        {
          "internalType": "uint8[]",
          "name": "",
          "type": "uint8[]"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
  ]
```