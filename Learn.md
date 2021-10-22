curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

instalamos o Rustup?

export PATH="/home/marciorcruz/.local/share/solana/install/active_release/bin:$PATH"

solana --version


nano ~/.bashrc

solana config set --url localhost

solana config set --url https://api.devnet.solana.com

Config File: /home/marciorcruz/.config/solana/cli/config.yml
RPC URL: https://api.devnet.solana.com 
WebSocket URL: wss://api.devnet.solana.com/ (computed)
Keypair Path: /home/marciorcruz/.config/solana/id.json 
Commitment: confirmed 

solana-keygen new --force


solana-keygen new --forceWrote new keypair to /home/marciorcruz/.config/solana/id.json
==================================================================================
pubkey: H88pMeAxnUVkBCgXNEDFZfXcSSLsseqJGtpQMTGud7pN
==================================================================================
Save this seed phrase and your BIP39 passphrase to recover your new keypair:
foot indoor uncover penalty federal melody setup myth annual diagram robust bunker

solana
solana


Wrote new keypair to /home/marciorcruz/.config/solana/id.json
==========================================================================
pubkey: FCwFjQU3hq9LhTmnLzx6Cbt8qDaaei9n263yk7SCVRnK
==========================================================================
Save this seed phrase and your BIP39 passphrase to recover your new keypair:
adjust slam age inspire sniff harvest reunion choice draw cake region lens

Requesting airdrop of 5 SOL

Signature: 5faFDqG2WuYz1ABLgT6TfMtQTrvmzSAwyhTh1dysUff7Hj2CSHFjNYo4Grr9gmeHNpJJPXwDjT5cxWM4dMHEzYTF

5 SOL

solana confirm -v 2NCMUjCGzWYpbLiU8fXbGRt6HgozU3eGHVSQvQRRWmxsTE8uvKuEucR98TrYci2x8Yx5vLqnAzu51qT7J1bstcFQ


RPC URL: https://api.devnet.solana.com
Default Signer Path: /home/marciorcruz/.config/solana/id.json
Commitment: confirmed

Transaction executed in slot 88990890:
  Block Time: 2021-10-21T23:44:16-03:00
  Recent Blockhash: E7Fa335qwgWRQxFudEdWbq5ajRRrZ5uW51orCYnGFtd9
  Signature 0: 2NCMUjCGzWYpbLiU8fXbGRt6HgozU3eGHVSQvQRRWmxsTE8uvKuEucR98TrYci2x8Yx5vLqnAzu51qT7J1bstcFQ
  Account 0: srw- 9B5XszUGdMaxCZ7uSQhPzdks5ZQSmWxrmzCSvtJ6Ns6g (fee payer)
  Account 1: -r-x MemoSq4gqABAXKb96qnH8TysNcWxMyWCqXgDLGmfcHr
  Instruction 0
    Program:   MemoSq4gqABAXKb96qnH8TysNcWxMyWCqXgDLGmfcHr (1)
    Data: "request too large; req: ◎10, cap: ◎5"
  Status: Ok
    Fee: ◎0.000005
    Account 0 balance: ◎1112433.359371342 -> ◎1112433.359366342
    Account 1 balance: ◎0.52149888
  Log Messages:
    Program MemoSq4gqABAXKb96qnH8TysNcWxMyWCqXgDLGmfcHr invoke [1]
    Program log: Memo (len 40): "request too large; req: ◎10, cap: ◎5"
    Program MemoSq4gqABAXKb96qnH8TysNcWxMyWCqXgDLGmfcHr consumed 33081 of 200000 compute units
    Program MemoSq4gqABAXKb96qnH8TysNcWxMyWCqXgDLGmfcHr success

Finalized


To deploy this program:
  $ solana program deploy /home/marciorcruz/Documents/projects/example-helloworld/dist/program/helloworld.so
The program address will default to this keypair (override with --program-id):
  /home/marciorcruz/Documents/projects/example-helloworld/dist/program/helloworld-keypair.json


  Program Id: J47Nku8AWTGx75nQibU27r5TMWnbsq3Eqm34vUARmLsV


  npm run start

> helloworld@0.0.1 start
> ts-node src/client/main.ts

Let's say hello to a Solana account...
Connection to cluster established: https://api.devnet.solana.com { 'feature-set': 1824749018, 'solana-core': '1.7.14' }
Using account FCwFjQU3hq9LhTmnLzx6Cbt8qDaaei9n263yk7SCVRnK containing 4.15099348 SOL to pay for fees
Using program J47Nku8AWTGx75nQibU27r5TMWnbsq3Eqm34vUARmLsV
Creating account AQHeWfu1fJNeqYiZRw4WuwXHz3JxWLrZsBE1aVLHAjuh to say hello to
Saying hello to AQHeWfu1fJNeqYiZRw4WuwXHz3JxWLrZsBE1aVLHAjuh
AQHeWfu1fJNeqYiZRw4WuwXHz3JxWLrZsBE1aVLHAjuh has been greeted 1 time(s)
Success