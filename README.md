# Solana Even Balance

A simple utility script to transfer SOL tokens between any amount of wallets given their keypairs.

## Example

```bash
./solana-even-balances ~/.config/solana/wallet-1.json ~/.config/solana/wallet-2.json ~/.config/solana/wallet-3.json

# Keypair: ~/.config/solana/wallet-1.json
# Pubkey: SomePubkey1111111111111111111111111111111111
# Balance: 1

# Keypair: ~/.config/solana/wallet-2.json
# Pubkey: SomePubkey2222222222222222222222222222222222
# Balance: 2

# Keypair: ~/.config/solana/wallet-3.json
# Pubkey: SomePubkey3333333333333333333333333333333333
# Balance: 3

# Planned commands:

# solana transfer -k ~/.config/solana/wallet-1.json SomePubkey1111111111111111111111111111111111 1

# Are you sure you want to continue? <y/N> y
# Executing...

# ...
```

## Warranty

This utility script comes with no warranty and is intended for use by experienced users only.
