# Read-only adapters

| Protocol Name                                                                                                                        | Description                                                                                                | Protocol Adapters                                                                                                                                                                                                                                                                                                                                                                                                                | Token Adapters                                                                                                                                         |
| ------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [Aave](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/aave){target=\_blank}                                   | Decentralized lending & borrowing protocol. Aave market.                                                   | [Asset Adapter](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/aave/AaveAssetAdapter.sol){target=\_blank} <br> [Debt adapter](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/aave/AaveDebtAdapter.sol){target=\_blank}                                                                                                                                                             | [AToken](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/aave/AaveTokenAdapter.sol){target=\_blank}                              |
| [Aave • Uniswap Market](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/aaveUniswap){target=\_blank}           | Decentralized lending & borrowing protocol. Uniswap market.                                                | <p><a href="https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/aaveUniswap/AaveUniswapAssetAdapter.sol">Asset adapter</a><br><a href="https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/aaveUniswap/AaveUniswapDebtAdapter.sol">Debt adapter</a></p>                                                                                                                                      | ["AToken Uniswap Market"](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/aave/AaveTokenAdapter.sol){target=\_blank}             |
| [Ampleforth](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/ampleforth){target=\_blank}                       | An adaptive money built on sound economics.                                                                | [Asset adapter](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/ampleforth/AmpleforthAdapter.sol){target=\_blank}                                                                                                                                                                                                                                                                                          | —                                                                                                                                                      |
| [Balancer](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/balancer){target=\_blank}                           | Non-custodial portfolio manager, liquidity provider, and price sensor.                                     | [Asset adapter](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/balancer/BalancerAdapter.sol){target=\_blank} supports all Balancer pools                                                                                                                                                                                                                                                                  | ["Balancer pool token"](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/balancer/BalancerTokenAdapter.sol){target=\_blank}       |
| [Bancor](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/bancor){target=\_blank}                               | Automated liquidity protocol.                                                                              | [Asset adapter](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/bancor/BancorAdapter.sol){target=\_blank} supports Bancor pools starting from version 11                                                                                                                                                                                                                                                   | ["SmartToken"](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/bancor/BancorTokenAdapter.sol){target=\_blank}                    |
| [Compound](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/compound){target=\_blank}                           | Decentralized lending & borrowing protocol.                                                                | <p><a href="https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/compound/CompoundAssetAdapter.sol">Asset adapter</a><br><a href="https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/compound/CompoundDebtAdapter.sol">Debt adapter</a><br><a href="https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/compound/CompoundGovernanceAdapter.sol">Governance adapter</a></p> | ["CToken"](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/compound/CompoundTokenAdapter.sol){target=\_blank}                    |
| [Curve](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/curve){target=\_blank}                                 | Exchange liquidity pool for stablecoin trading. Supports all pools.                                        | [Asset adapter](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/curve/CurveAdapter.sol){target=\_blank}                                                                                                                                                                                                                                                                                                    | ["Curve pool token"](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/curve/CurveTokenAdapter.sol){target=\_blank}                |
| [DDEX • Lending](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/ddexLending){target=\_blank}                  | Decentralized lending and borrowing                                                                        | [Asset adapter](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/ddexLending/DdexLendingAssetAdapter.sol){target=\_blank}                                                                                                                                                                                                                                                                                   | —                                                                                                                                                      |
| [DDEX • Margin](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/ddexMargin){target=\_blank}                    | Decentralized margin trading                                                                               | <p><a href="https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/ddexMargin/DdexMarginAssetAdapter.sol">Asset adapter</a><br><a href="https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/ddexMargin/DdexMarginDebtAdapter.sol">Debt adapter</a></p>                                                                                                                                          | —                                                                                                                                                      |
| [DDEX • Spot](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/ddexSpot){target=\_blank}                        | Decentralized trading                                                                                      | [Asset adapter](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/ddexSpot/DdexSpotAssetAdapter.sol){target=\_blank}                                                                                                                                                                                                                                                                                         | —                                                                                                                                                      |
| [DeFi Money Market](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/dmm){target=\_blank}                       | Crypto through revenue-producing real world assets.                                                        | [Asset adapter](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/dmm/DmmAssetAdapter.sol){target=\_blank}                                                                                                                                                                                                                                                                                                   | ["MToken"](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/dmm/DmmTokenAdapter.sol){target=\_blank}                              |
| [dYdX](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/dydx){target=\_blank}                                   | Decentralized trading platform. All 4 markets (WETH, SAI, USDC, DAI){target=\_blank} are supported.        | <p><a href="https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/dydx/DyDxAssetAdapter.sol">Asset adapter</a><br><a href="https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/dydx/DyDxDebtAdapter.sol">Debt adapter</a></p>                                                                                                                                                                  | —                                                                                                                                                      |
| [Idle](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/idle){target=\_blank}                                   | Yield aggregator for lending platforms.                                                                    | [Asset adapter](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/idle/IdleAdapter.sol){target=\_blank}                                                                                                                                                                                                                                                                                                      | ["IdleToken"](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/idle/IdleTokenAdapter.sol){target=\_blank}                         |
| [iearn.finance (v2/v3){target=\_blank}](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/iearn){target=\_blank} | Yield aggregator for lending platforms. Protocol adapter is duplicated for v2 and v3 versions of protocol. | [Asset adapter](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/iearn/IearnAdapter.sol){target=\_blank}                                                                                                                                                                                                                                                                                                    | ["YToken"](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/iearn/IearnTokenAdapter.sol){target=\_blank}                          |
| [KyberDAO](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/kyber){target=\_blank}                              | Platform that allows KNC token holders to participate in governance.                                       | [Asset adapter](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/kyber/KyberAssetAdapter.sol){target=\_blank}                                                                                                                                                                                                                                                                                               | —                                                                                                                                                      |
| [Chai](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/maker){target=\_blank}                                  | A simple ERC20 wrapper over the Dai Savings Protocol.                                                      | [Asset adapter](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/maker/ChaiAdapter.sol){target=\_blank}                                                                                                                                                                                                                                                                                                     | ["Chai token"](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/maker/ChaiTokenAdapter.sol){target=\_blank}                       |
| [Dai Savings Protocol](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/maker){target=\_blank}                  | Decentralized lending protocol.                                                                            | [Asset adapter](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/maker/DSRAdapter.sol){target=\_blank}                                                                                                                                                                                                                                                                                                      | —                                                                                                                                                      |
| [Maker Governance](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/maker){target=\_blank}                      | MKR tokens locked on the MakerDAO governance contracts.                                                    | [Asset adapter](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/maker/MakerGovernanceAdapter.sol){target=\_blank}                                                                                                                                                                                                                                                                                          | —                                                                                                                                                      |
| [Multi-Collateral Dai](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/maker){target=\_blank}                  | Collateralized loans on Maker.                                                                             | <p><a href="https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/maker/MCDAssetAdapter.sol">Asset adapter</a><br><a href="https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/maker/MCDDebtAdapter.sol">Debt adapter</a></p>                                                                                                                                                                  | —                                                                                                                                                      |
| [mStable](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/mstable){target=\_blank}                             | mStable unifies stablecoins, lending and swapping into one standard.                                       | [Asset adapter](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/mstable/MstableAssetAdapter.sol){target=\_blank}                                                                                                                                                                                                                                                                                           | ["Masset"](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/mstable/MstableTokenAdapter.sol){target=\_blank}                      |
| [PoolTogether](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/poolTogether){target=\_blank}                   | Decentralized no-loss lottery. Supports SAI, DAI, and USDC pools.                                          | [Asset adapter](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/poolTogether/PoolTogetherAdapter.sol){target=\_blank}                                                                                                                                                                                                                                                                                      | ["PoolTogether pool"](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/poolTogether/PoolTogetherTokenAdapter.sol){target=\_blank} |
| [Synthetix](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/synthetix){target=\_blank}                         | Synthetic assets protocol. Asset adapter returns amount of SNX locked as collateral.                       | <p><a href="https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/synthetix/SynthetixAssetAdapter.sol">Asset adapter</a><br><a href="https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/synthetix/SynthetixDebtAdapter.sol">Debt adapter</a></p>                                                                                                                                              | —                                                                                                                                                      |
| [TokenSets](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/tokenSets){target=\_blank}                         | Automated asset management strategies.                                                                     | [Asset adapter](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/tokenSets/TokenSetsAdapter.sol){target=\_blank}                                                                                                                                                                                                                                                                                            | ["SetToken"](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/tokenSets/TokenSetsTokenAdapter.sol){target=\_blank}                |
| [Uniswap V1](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/uniswap){target=\_blank}                          | Automated liquidity protocol.                                                                              | [Asset adapter](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/uniswap/UniswapV1Adapter.sol){target=\_blank} supports all Uniswap V1 pools                                                                                                                                                                                                                                                                | ["Uniswap V1 pool token"](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/uniswap/UniswapV1TokenAdapter.sol){target=\_blank}     |
| [Uniswap V2](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/uniswap){target=\_blank}                          | Automated liquidity protocol.                                                                              | [Asset adapter](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/uniswap/UniswapV2Adapter.sol){target=\_blank} supports all Uniswap V2 pools                                                                                                                                                                                                                                                                | ["Uniswap V2 pool token"](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/uniswap/UniswapV2TokenAdapter.sol){target=\_blank}     |
| [0x Staking](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/zrx){target=\_blank}                              | Liquidity rewards for staking ZRX.                                                                         | [Asset adapter](https://github.com/zeriontech/defi-sdk/blob/master/contracts/adapters/zrx/ZrxAdapter.sol){target=\_blank}                                                                                                                                                                                                                                                                                                        | —                                                                                                                                                      |