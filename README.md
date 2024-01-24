# Deployment of smart contract with crud functions to public testnet and accessing via node.js and web3 library

# Usage Examples
  
1. Check Balance

Check the balance of a user's wallet address.
node script.js balance


2. Transfer Tokens

Transfer a specified amount of tokens to another wallet address.
node script.js transfer --from=0x427D8ACFe3820420DEBB19c0D64eb098b8B42Fb4 --to=0x1234567890123456789012345678901234567890 --amount=100


3. Burn Tokens

Burn (destroy) a specified amount of tokens from the script executor's wallet.
node script.js burn --amount=50


4. Mint Tokens

Mint (create) a specified amount of tokens and assign them to a specific wallet address.
node script.js mint --to=0x1234567890123456789012345678901234567890 --amount=200


5. Get Total Supply

Retrieve the total supply of tokens.
node script.js getTotalSupply


6. Get Transaction Sender

Retrieve the sender's address of the latest transaction.
node script.js getTransactionSender


7. Get Transaction Receiver

Retrieve the contract's address as the receiver of the latest transaction.
node script.js getTransactionReceiver


8. Transfer Ownership

Transfer ownership of the contract to a new administrator.
node script.js transferOwnership --newAdmin=0xNewAdminAddress


9. Mint to Admin

Mint a specified amount of tokens and assign them to the contract's administrator.
node script.js mintToAdmin --amount=100


# Demo screenshots
<img width="1440" alt="Screenshot 2024-01-25 at 00 37 09" src="https://github.com/mysteryman04/blockchain2/assets/112248124/677213e8-6cbf-492a-b4a0-b497375fee67">
<img width="1440" alt="Screenshot 2024-01-25 at 00 37 34" src="https://github.com/mysteryman04/blockchain2/assets/112248124/8775f03b-0c60-42d7-87be-b536731ef987">
<img width="1440" alt="Screenshot 2024-01-25 at 00 37 53" src="https://github.com/mysteryman04/blockchain2/assets/112248124/e025bd76-bb9f-4651-a699-1f4ef5c4c4c8">
<img width="1440" alt="Screenshot 2024-01-25 at 00 38 53" src="https://github.com/mysteryman04/blockchain2/assets/112248124/31b4a01d-7c7b-4501-8a99-3353a31fc880">
<img width="574" alt="Screenshot 2024-01-25 at 00 40 21" src="https://github.com/mysteryman04/blockchain2/assets/112248124/712ab2ad-30dd-4d4d-9994-e966074b67b2">
<img width="1440" alt="Screenshot 2024-01-25 at 00 47 32" src="https://github.com/mysteryman04/blockchain2/assets/112248124/63014e60-92c6-4722-9623-d4253e2209d0">
<img width="1440" alt="Screenshot 2024-01-25 at 00 56 20" src="https://github.com/mysteryman04/blockchain2/assets/112248124/998256ba-9ba4-431a-8885-abfa97985457">
<img width="1440" alt="Screenshot 2024-01-25 at 00 58 32" src="https://github.com/mysteryman04/blockchain2/assets/112248124/dd0200ad-1fc9-48d1-9203-5e2b409f1901">
<img width="1440" alt="Screenshot 2024-01-25 at 01 37 45" src="https://github.com/mysteryman04/blockchain2/assets/112248124/d5c1081b-40f8-40d9-9f01-40bba48aa0d8">

# Examples
Example 1: Check Balance

node script.js balance
This command checks the balance of the default wallet address.

Example 2: Transfer Tokens

node script.js transfer --from=0xSenderAddress --to=0xRecipientAddress --amount=50
This command transfers 50 tokens from the specified sender address to the recipient address.

Example 3: Burn Tokens

node script.js burn --amount=25
This command burns (destroys) 25 tokens from the script executor's wallet.

Example 4: Mint Tokens

node script.js mint --to=0xRecipientAddress --amount=100
This command mints (creates) 100 tokens and assigns them to the specified recipient address.


# LICENSE
https://github.com/OpenZepp
elin/openzeppelin-
contracts/blob/master/LICENSE
<br>
https://spdx.org/licenses/MIT.html

