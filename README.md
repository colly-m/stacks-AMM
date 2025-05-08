Full stack applications on Stacks and build a relatively more complex DeFi protocol. Specifically, we'll create a fully decentralized exchange (DEX) on Stacks and then build a frontend for it.

The DEX will allow anyone to create a new trading pool permissionlessly, let people add/remove liquidity and become LPs to earn fees, and allow traders to swap tokens freely. 

Any user should be able to permissionlessly create a new trading pool on the DEX for any two SIP-010 tokens and supply some initial liquidity. This is important because when a new token is created, it must be possible to also create a trading pool for it to enable users to transact in that asset.

Any user should be able to add liquidity to a pool created on the DEX

Any user who has previously added liquidity should be able to remove their liquidity from the DEX

Any user should be able to swap between two assets of any given trading pool on the DEX

Any swap taking place on the DEX must charge a small amount of fees to the trader that is redistributed back to liquidity providers for supplying liquidity that enables those trades to happen

It must not be possible to create two distinct trading pools for the exact same pair of tokens (i.e. there shouldn't be two separate A/B pools)

This is all on the contract side of things. On the frontend, we'll also set up a website where a user can connect their wallet and carry out these actions without needing to interact directly with the contract code.
