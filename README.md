| Strategy | Address     | Description|
| :---        | :----       |:----       |
|  [Rebalancer YFI JointProvider YFI-WETH](https://github.com/tonkers-kuma/strategy-rebalancer)     |  [0x4050eB90c15F27aa75b5CFcb934a26fDE60Cf9Cb](https://etherscan.io/address/0x4050eB90c15F27aa75b5CFcb934a26fDE60Cf9Cb) | Supplies YFI as half of a join liquidity provider for the YFI-WETH Oracle Weighted Pool on Balancer.fi. Rewards are harvested, split between the two pairs, sold for more YFI, and deposited back into the strategy.|
| StrategyGenLevAAVE-Flashmint     |  [0xDfFe2E8B9DD8Cc0367AAED727c07a8d2bB36Ed8b](https://etherscan.io/address/0xDfFe2E8B9DD8Cc0367AAED727c07a8d2bB36Ed8b) | Supplies YFI on AAVE and flashmints an additional amount of YFI to maximize stkAAVE earnings. Flashmints are used to mint DAI from MakerDAO to flashlend and increase the position, boosting the APY. stkAAVE is harvested, sold for more YFI, and deposited back into the strategy.|
| [StrategyLenderYieldOptimiser](https://github.com/Grandthrax/yearnV2-generic-lender-strat)     |  [0xeE697232DF2226c9fB3F02a57062c4208f287851](https://etherscan.io/address/0xeE697232DF2226c9fB3F02a57062c4208f287851) | Lends sUSD on AAVE and Cream to gain interest and accumulate staked AAVE as rewards. When the staked AAVE unlocks the AAVE will be harvested, sold for more sUSD, and re-deposited into the vault.|
| [StrategyGenericLevCompFarmWeth](https://github.com/Grandthrax/YearnV2-Generic-Lev-Comp-Farm)     |  [0x83B6211379c26E0bA8d01b9EcD4eE1aE915630aa](https://etherscan.io/address/0x83B6211379c26E0bA8d01b9EcD4eE1aE915630aa) | Supplies ETH on Compound and borrows an additional amount of ETH to maximize COMP earnings. Flashloans are used to obtain additional ETH from dYdX in order to gain additional leverage and boost the APY. Earned COMP is harvested and sold for more ETH and re-deposited into the vault.|





