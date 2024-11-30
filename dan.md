

## Tendermint Liquidity v1beta1 Transactions

This document outlines the protocol buffer messages for the Tendermint Liquidity v1beta1 transaction messages. Protocol buffers are a language-neutral, platform-neutral, extensible mechanism for serializing structured data.

### Transaction Types

The messages in this file define different types of transactions that can be sent to the Tendermint Liquidity protocol. These transactions include:

- **Deposit**: A transaction to deposit funds into a liquidity pool.
- **Withdraw**: A transaction to withdraw funds from a liquidity pool.
- **Swap**: A transaction to swap tokens between two liquidity pools.
- **ProvideLiquidity**: A transaction to provide liquidity to a liquidity pool.
- **RemoveLiquidity**: A transaction to remove liquidity from a liquidity pool.
- **SwapExactTokensForTokens**: A transaction to swap tokens between two liquidity pools, while ensuring that the user receives the same amount of tokens in total.

These transactions are used to allow users to participate in the Tendermint Liquidity protocol and to exchange tokens between different liquidity pools.

