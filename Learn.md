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