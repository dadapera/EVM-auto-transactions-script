This project lets you automatically perform transactions on a custom EVM blockchain.

Create a .env file with a 'PRIVATE_KEY' variable in it. \
This has to be the private key of the wallet you want to operate.

Then in main.js, customize the constants with the required addresses and ABI of the tokens and contracts you want to interact. \
Customize the interactions functions to adapt them to your use case.

To launch the program run it:
```bash
node main.js <iterations>
```
\<iterations> is the number of iteration loops to be performed.