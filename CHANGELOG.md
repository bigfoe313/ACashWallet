# Changelog

## Current Master

## 5.2.6 Tue Sep 21 2021

- [#466](https://github.com/poanetwork/nifty-wallet/pull/466) - Update NPM dependencies to match Node v14.x
- [#403](https://github.com/poanetwork/nifty-wallet/pull/403), [#467](https://github.com/poanetwork/nifty-wallet/pull/467) - Add D'CENT hardware wallet support

## 5.2.5 Fri May 21 2021

- [#459](https://github.com/poanetwork/nifty-wallet/pull/459) - (Fix) Phishing detection

## 5.2.4 Sat Feb 27 2021

- [#451](https://github.com/poanetwork/nifty-wallet/pull/451) - (Fix) Fix export private key when switching between chains
- [#450](https://github.com/poanetwork/nifty-wallet/pull/450) - (Chore) Remove deprecated Infura network status check
- [#443](https://github.com/poanetwork/nifty-wallet/pull/443) - (Fix) Fire 'confirmation', 'receipt' events

## 5.2.3 Fri Jan 15 2021

- [#441](https://github.com/poanetwork/nifty-wallet/pull/441) - Replace Infura Mainnet endpoint with custom one

## 5.2.2 Tue Dec 29 2020

- [#437](https://github.com/poanetwork/nifty-wallet/pull/437) - Support getting proxy implementation address by following EIP-1967
- [#436](https://github.com/poanetwork/nifty-wallet/pull/436) - Allow master copy pattern in importing of proxy contract
- [#435](https://github.com/poanetwork/nifty-wallet/pull/435) - Allow array input type in contracts interactions
- [#434](https://github.com/poanetwork/nifty-wallet/pull/434) - Add support of tuple type at interaction with read-only contract methods
- [#432](https://github.com/poanetwork/nifty-wallet/pull/432) - bump rsk-contract-metadata dependency

## 5.2.1 Fri Dec 04 2020

- [#429](https://github.com/poanetwork/nifty-wallet/pull/429) - Allow Ledger signMessage method

## 5.2.0 Fri Nov 13 2020

- [#427](https://github.com/poanetwork/nifty-wallet/pull/427) - Fix support of eth_signTypedData_v4 (eip-712)
- [#426](https://github.com/poanetwork/nifty-wallet/pull/426) - Update inpage provider: add ethereum.request method support
- [#411](https://github.com/poanetwork/nifty-wallet/pull/411) - GitHub actions CI

## 5.1.6 Tue Oct 27 2020

- [#419](https://github.com/poanetwork/nifty-wallet/pull/419) - Add 10% margin for gas price in case of RSK chains

## 5.1.5 Tue Oct 20 2020

- [#416](https://github.com/poanetwork/nifty-wallet/pull/416) - Change Copy token address text
- [#415](https://github.com/poanetwork/nifty-wallet/pull/415) - Fix broken Blockscout's token transfers page link

## 5.1.4 Tue Aug 04 2020

Removal of webRequest permission was not applied in the previous version. Applying it here.

## 5.1.3 Tue Aug 04 2020

- [#407](https://github.com/poanetwork/nifty-wallet/pull/407) - Remove excess extension permissions: webRequest

## 5.1.2 Fri Jul 10 2020

- [#400](https://github.com/poanetwork/nifty-wallet/pull/400) - (Fix) Fix RNS resolving
- [#399](https://github.com/poanetwork/nifty-wallet/pull/399) - (Chore) Set 10 Gwei gas price for POA and Sokol chains
- [#399](https://github.com/poanetwork/nifty-wallet/pull/399) - (Fix) Fix 0 gas price when on POA, Sokol, xDai chains when confirmation popup is called from dApp
- [#398](https://github.com/poanetwork/nifty-wallet/pull/398) - (Chore) New RSK testnet default tokens
- [#398](https://github.com/poanetwork/nifty-wallet/pull/398) - (Fix) Etherscan link for Ethereum Mainnet
- [#398](https://github.com/poanetwork/nifty-wallet/pull/398) - (Chrore) Update NPM deps to fix known vulnerabilities

## 5.1.1 Mon Jun 15 2020

- [#393](https://github.com/poanetwork/nifty-wallet/pull/393) - (Feature) "Send all" option for tokens transfer
- [#391](https://github.com/poanetwork/nifty-wallet/pull/391) - (Feature) Gas price oracles npm package integration
- [#389](https://github.com/poanetwork/nifty-wallet/pull/389) - (Feature) Support 24 words mnemonic phrase
- [#388](https://github.com/poanetwork/nifty-wallet/pull/388) - (Feature) "Send all" option for simple coin transfers
- [#385](https://github.com/poanetwork/nifty-wallet/pull/385) - (Feature) Display value of current pending tx's nonce on send tx screen
- [#384](https://github.com/poanetwork/nifty-wallet/pull/384) - (Fix) placement of HW Connect button title
- [#383](https://github.com/poanetwork/nifty-wallet/pull/383) - (Chore) Replace POA-ETH Binance link to POA-BTC
- [#382](https://github.com/poanetwork/nifty-wallet/pull/382) - (Fix) replace vulnerable npm dependencies with newer versions of packages, update chromedriver to match the latest Google Chrome release
- [#381](https://github.com/poanetwork/nifty-wallet/pull/381) - (Feature) Add RNS integration
- [#381](https://github.com/poanetwork/nifty-wallet/pull/381) - (Fix) ENS/RNS integration when sending tokens

## 5.1.0 Tue May 12 2020

- [#356](https://github.com/poanetwork/nifty-wallet/pull/356) - (Backwards-compatibility feature) Custom derivation paths and access to funds in accounts derived from ETH dPath
- [#379](https://github.com/poanetwork/nifty-wallet/pull/379) - (Feature) Ability to set custom nonce of tx
- [#377](https://github.com/poanetwork/nifty-wallet/pull/377) - (Fix) Sign message screen: do not decode message if it is not hex encoded
- [#364](https://github.com/poanetwork/nifty-wallet/pull/364) - (Fix) notifications order in batch requests

## 5.0.3 Fri May 01 2020

- [#373](https://github.com/poanetwork/nifty-wallet/pull/373) - (Feature) Add STAKE token
- [#372](https://github.com/poanetwork/nifty-wallet/pull/372) - (Chore) Update RSK contracts metadata repo
- [#369](https://github.com/poanetwork/nifty-wallet/pull/369) - (Fix) RSK: fix GasPrice calculation (changed interface of minimumGasPrice - hex instead of integer)
- [#368](https://github.com/poanetwork/nifty-wallet/pull/368) - (Fix) Ability to import Keystore file if it is not secured by password
- [#366](https://github.com/poanetwork/nifty-wallet/pull/366) - (Fix) Increase max token symbol length up to 12
- [#363](https://github.com/poanetwork/nifty-wallet/pull/363) - (Fix) token decimals display in pending tx screen

## 5.0.2 Thu Apr 16 2020

- [#359](https://github.com/poanetwork/nifty-wallet/pull/359) - (Fix) Fix exposed accounts in wallet locked state
- [#355](https://github.com/poanetwork/nifty-wallet/pull/355) - (Feature) Add RSK/testnet default tokens
- [#354](https://github.com/poanetwork/nifty-wallet/pull/354) - (Fix) `accountsChanged` event emittance (a part of EIP-1193)
- [#353](https://github.com/poanetwork/nifty-wallet/pull/353) - (Fix) synchronous eth_accounts request

## 5.0.1 Mon Apr 06 2020

- [#347](https://github.com/poanetwork/nifty-wallet/pull/347) - Rollback custom dPath for RSK/ETC

## 5.0.0 Tue Mar 31 2020

- [#340](https://github.com/poanetwork/nifty-wallet/pull/340), [#342](https://github.com/poanetwork/nifty-wallet/pull/342) - (Feature) Update in-page provider (EIP-1193)
- [#334](https://github.com/poanetwork/nifty-wallet/pull/334) - (Feature) Ability to set tx value for payable methods
- [#333](https://github.com/poanetwork/nifty-wallet/pull/333) - (Fix) Support RSK testnet explorer links
- [#332](https://github.com/poanetwork/nifty-wallet/pull/332) - (Chore) Return to main screen from removal of imported account
- [#330](https://github.com/poanetwork/nifty-wallet/pull/330) - (Fix) Derive correct addresses for custom networks (RSK/ETC)
- [#329](https://github.com/poanetwork/nifty-wallet/pull/329) - (Fix) Connect to unknown private network fix
- [#326](https://github.com/poanetwork/nifty-wallet/pull/326) - (Chore) HTTP2 RPC endpoints for POA and xDai
- [#324](https://github.com/poanetwork/nifty-wallet/pull/324) - (Chore) Whitelist Geon token
- [#323](https://github.com/poanetwork/nifty-wallet/pull/323) - (Chore) update Mainnet tokens metadata
- [#322](https://github.com/poanetwork/nifty-wallet/pull/322) - (Fix) Update explorers links
- [#318](https://github.com/poanetwork/nifty-wallet/pull/318) - (Fix) pasting of ABI for contract type account
- [#317](https://github.com/poanetwork/nifty-wallet/pull/317) - (Fix) path to derive accounts in HD wallets for RSK, ETC

## 4.11.10 Tue Feb 04 2020

- [#313](https://github.com/poanetwork/nifty-wallet/pull/313) - Change Ethereum classic RPC endpoint

## 4.11.9 Thu Aug 22 2019

- [#303](https://github.com/poanetwork/nifty-wallet/pull/303): (Feature) Add Pocket Network
- [#308](https://github.com/poanetwork/nifty-wallet/pull/308): (Fix) Fix gas price calculation

## 4.11.8 Wed Jul 03 2019

- [#305](https://github.com/poanetwork/nifty-wallet/pull/305): (Feature) gas price for RSK from the last block
- [#298](https://github.com/poanetwork/nifty-wallet/pull/298): (Feature) isNiftyWallet property added
- [#299](https://github.com/poanetwork/nifty-wallet/pull/299): (Upgrade) Node 10 support
- [#306](https://github.com/poanetwork/nifty-wallet/pull/306): (Fix) Replace Goerli RPC endpoint
- [#302](https://github.com/poanetwork/nifty-wallet/pull/302): (Fix) Return scrolls in dropdowns

## 4.11.7 Tue Jun 25 2019

- [#294](https://github.com/poanetwork/nifty-wallet/pull/294): Address checksum for RSK chains. RSKIP60
- [#293](https://github.com/poanetwork/nifty-wallet/pull/293): RSK tx status fix
- [#292](https://github.com/poanetwork/nifty-wallet/pull/292): Fix gas price for RSK
- [#291](https://github.com/poanetwork/nifty-wallet/pull/291): Fix fiat value for RSK
- [#290](https://github.com/poanetwork/nifty-wallet/pull/290): gas limit fix for RSK chain
- [#289](https://github.com/poanetwork/nifty-wallet/pull/289): RSK testnet support

## 4.11.6 Thu Jun 06 2019

- [#285](https://github.com/poanetwork/nifty-wallet/pull/285): (Feature) Add RSK mainnet support
- [#284](https://github.com/poanetwork/nifty-wallet/pull/284): (Feature) Blockscout links for all chains
- [#286](https://github.com/poanetwork/nifty-wallet/pull/286): (Fix) Import of proxy contracts for eth chains
- [#283](https://github.com/poanetwork/nifty-wallet/pull/283): (Fix) Display POA Core name

## 4.11.5 Thu Apr 18 2019

- [#279](https://github.com/poanetwork/nifty-wallet/pull/279): (Fix) utf8 encoding in contentscript.js

## 4.11.4 Mon Apr 15 2019

- [#277](https://github.com/poanetwork/nifty-wallet/pull/277): (Fix) USD price for ETC coin
- [#276](https://github.com/poanetwork/nifty-wallet/pull/276): (Fix) Remove js obfuscation

## 4.11.3 Fri Mar 29 2019

- [#272](https://github.com/poanetwork/nifty-wallet/pull/272): Update Classic RPC endpoint

## 4.11.2 Wed Mar 27 2019

- [#270](https://github.com/poanetwork/nifty-wallet/pull/270): (Feature) Support of gas price oracles for ETH, ETC
- [#268](https://github.com/poanetwork/nifty-wallet/pull/268): (Feature) Support of Ethereum Classic chain

## 4.11.1 Wed Mar 20 2019

- [#266](https://github.com/poanetwork/nifty-wallet/pull/266): (Fix) Support of the latest trezor-connect version 7
- [#263](https://github.com/poanetwork/nifty-wallet/pull/263): (Refactoring) Refine dropdown components

## 4.11.0 Fri Feb 08 2019

### Features

- [#262](https://github.com/poanetwork/nifty-wallet/pull/262): (Feature) Add native support of Görli testnet
- [#254](https://github.com/poanetwork/nifty-wallet/pull/254): (Feature) HitBTC exchange for core POA network
- [#251](https://github.com/poanetwork/nifty-wallet/pull/251): (Feature) Delegate Proxy contract type (EIP-897)
- [#252](https://github.com/poanetwork/nifty-wallet/pull/252): (Feature) Simultaneous support of Trezor and Ledger HD wallets
- [#250](https://github.com/poanetwork/nifty-wallet/pull/250): (Feature) Support of multiple accounts from Trezor HD wallet for single session
- [#237](https://github.com/poanetwork/nifty-wallet/pull/237): (Feature) Multiple Ledger accounts for one session
- [#249](https://github.com/poanetwork/nifty-wallet/pull/249): (Feature) Textarea instead of input for array type outputs in contract calls
- [#247](https://github.com/poanetwork/nifty-wallet/pull/247): (Update) Change exchange rate API endpoint

### Fixes

- [#261](https://github.com/poanetwork/nifty-wallet/pull/261): (Fix) Clear timeout on componentWillUnmount in connect hardware screen
- [#260](https://github.com/poanetwork/nifty-wallet/pull/260): (Fix) Remove unit && integration tests for unused components
- [#258](https://github.com/poanetwork/nifty-wallet/pull/258): (Fix) ENS validation fix for Send transaction screen
- [#257](https://github.com/poanetwork/nifty-wallet/pull/257): (Fix) Replace poa.infura.io with core.poa.network in e2e
- [#248](https://github.com/poanetwork/nifty-wallet/pull/248): (Fix) validation for calling data from contract: Default `0x` value for _bytes_ field type should be set only for input fields

### Refactoring

- [#259](https://github.com/poanetwork/nifty-wallet/pull/259): (Refactoring) Refactor copy component
- [#256](https://github.com/poanetwork/nifty-wallet/pull/256): (Refactoring) Send-token component
- [#253](https://github.com/poanetwork/nifty-wallet/pull/253): (Refactoring) Refactor network props enums

## 4.10.1 Sat Dec 29 2018

- [#219](https://github.com/poanetwork/nifty-wallet/pull/219): (Feature) Multiple output fields support for contract call
- [#229](https://github.com/poanetwork/nifty-wallet/pull/229): (Feature) Select for Boolean type input in contract call/execution
- [#239](https://github.com/poanetwork/nifty-wallet/pull/239): (Feature) Reorder contract executors: owners are first
- [#233](https://github.com/poanetwork/nifty-wallet/pull/233): (Feature) Copy contract ABI from account menu
- [#226](https://github.com/poanetwork/nifty-wallet/pull/226): (Feature) Different label for HD account
- [#238](https://github.com/poanetwork/nifty-wallet/pull/238): (Fix) Unlock back contract account on rejecting/accepting of contract execution transaction
- [#224](https://github.com/poanetwork/nifty-wallet/pull/224): (Fix) Bytes is not a mandatory input in contract call/execution
- [#232](https://github.com/poanetwork/nifty-wallet/pull/232): (Fix) *Execute methods* button instead of *Buy*/*Send* for contract type account


## 4.10.0 Tue Dec 04 2018

- [#212](https://github.com/poanetwork/nifty-wallet/pull/212): (Feature) Interact with smart-contracts
- [#209](https://github.com/poanetwork/nifty-wallet/pull/209): (Fix) Enhance custom RPC validation

## 4.9.0 Mon Nov 26 2018

- [#183](https://github.com/poanetwork/nifty-wallet/pull/183), [#205](https://github.com/poanetwork/nifty-wallet/pull/205): HD wallets support
- [#199](https://github.com/poanetwork/nifty-wallet/pull/199): (Fix) Doubled fired events
- [#190](https://github.com/poanetwork/nifty-wallet/pull/190): (Fix) Display non-zero fiat value
- [#189](https://github.com/poanetwork/nifty-wallet/pull/189): (Fix) Branding of phishing detection page
- [#207](https://github.com/poanetwork/nifty-wallet/pull/207): (Fix) Format of token balance in the tokens list
- [#191](https://github.com/poanetwork/nifty-wallet/pull/191): (Fix) Handle: Cannot read property address of undefined
- [#202](https://github.com/poanetwork/nifty-wallet/pull/202): (Fix) Detect tokens: handle undefined tokenAddresses
- [#203](https://github.com/poanetwork/nifty-wallet/pull/203): (Fix) Handle undefined txParams
- [#204](https://github.com/poanetwork/nifty-wallet/pull/204): (Fix) Handle e.trim is not a function

## 4.8.8 Fri Nov 09 2018

- [#186](https://github.com/poanetwork/nifty-wallet/pull/186): (Fix) Do not retrieve token metadata for non-token pending tx
- [#184](https://github.com/poanetwork/nifty-wallet/pull/184): (Update) Rename repository
- [#182](https://github.com/poanetwork/nifty-wallet/pull/182): (Refactoring) Generalizing of retrieving of faucets/exchanges links

## 4.8.7 Tue Nov 06 2018

- [#180](https://github.com/poanetwork/metamask-extension/pull/180), [#172](https://github.com/poanetwork/metamask-extension/pull/172), [#169](https://github.com/poanetwork/metamask-extension/pull/169), [#165](https://github.com/poanetwork/metamask-extension/pull/165), [#160](https://github.com/poanetwork/metamask-extension/pull/160): (Fix) Memory leaks
- [#177](https://github.com/poanetwork/metamask-extension/pull/177): (Fix) Zero balance display instead of "None"
- [#175](https://github.com/poanetwork/metamask-extension/pull/175), [#176](https://github.com/poanetwork/metamask-extension/pull/176), [#178](https://github.com/poanetwork/metamask-extension/pull/178): (Feature) Auto-detect tokens for POA
- [#164](https://github.com/poanetwork/metamask-extension/pull/164): (Fix) Confirm token transfer page display fix

## 4.8.6 Thu Oct 18 2018

- [#153](https://github.com/poanetwork/metamask-extension/pull/153), [#154](https://github.com/poanetwork/metamask-extension/pull/154), [#158](https://github.com/poanetwork/metamask-extension/pull/158): (Feature) xDai chain support
- [#149](https://github.com/poanetwork/metamask-extension/pull/149), [#150](https://github.com/poanetwork/metamask-extension/pull/150): (Fix) Add custom tokens validation
- [#145](https://github.com/poanetwork/metamask-extension/pull/145), [#146](https://github.com/poanetwork/metamask-extension/pull/146): (Feature) Transfer tokens
- [#142](https://github.com/poanetwork/metamask-extension/pull/142), [#143](https://github.com/poanetwork/metamask-extension/pull/143): (Feature) Token menu: view in explorer/copy/remove
- [#140](https://github.com/poanetwork/metamask-extension/pull/140): (Feature) Search tokens in POA network
- [#135](https://github.com/poanetwork/metamask-extension/pull/135), [#138](https://github.com/poanetwork/metamask-extension/pull/138), [#141](https://github.com/poanetwork/metamask-extension/pull/141): (Feature) Search tokens (in Mainnet)
- [#132](https://github.com/poanetwork/metamask-extension/pull/132), [#133](https://github.com/poanetwork/metamask-extension/pull/133): (Fix) empty keyring on wrong password
- [#130](https://github.com/poanetwork/metamask-extension/pull/130): (Fix) remove test domains form ENS resolver
- [#128](https://github.com/poanetwork/metamask-extension/pull/128): (Fix) Clear an error on successful response from tokens balances
- [#127](https://github.com/poanetwork/metamask-extension/pull/127): (Fix) Error is constantly shown through screens
- [#122](https://github.com/poanetwork/metamask-extension/pull/122): (Fix) Remove fox animation components
- [#120](https://github.com/poanetwork/metamask-extension/pull/120): (Feature) Update token's balance on account switch
- [#119](https://github.com/poanetwork/metamask-extension/pull/119): (Fix) Shapeshift logo from local storage
- [#118](https://github.com/poanetwork/metamask-extension/pull/118), [#123](https://github.com/poanetwork/metamask-extension/pull/123): (Feature) Copy button from main account page
- [#104](https://github.com/poanetwork/metamask-extension/pull/104), [#108](https://github.com/poanetwork/metamask-extension/pull/108), [#109](https://github.com/poanetwork/metamask-extension/pull/109), [#116](https://github.com/poanetwork/metamask-extension/pull/116), [#121](https://github.com/poanetwork/metamask-extension/pull/121): (Feature) Support of Firefox
- [#103](https://github.com/poanetwork/metamask-extension/pull/103): (Fix) to display localhost:8545 in Settings
- [#101](https://github.com/poanetwork/metamask-extension/pull/101): (Fix) Catch Promises errors
- [#99](https://github.com/poanetwork/metamask-extension/pull/99), [#100](https://github.com/poanetwork/metamask-extension/pull/100): (Fix) Validate custom RPC
- [#98](https://github.com/poanetwork/metamask-extension/pull/98): (Feature) Unlimited amount of custom RPC

## 4.8.5 Mon Aug 27 2018

- [#94](https://github.com/poanetwork/metamask-extension/pull/94): (Fix) Force open notification popup
- [#93](https://github.com/poanetwork/metamask-extension/pull/93): (Fix) Empty pending tx screen after logout/login
- [#91](https://github.com/poanetwork/metamask-extension/pull/91): (Fix) Confirm tx notification popup: network name
- [#89](https://github.com/poanetwork/metamask-extension/pull/89), [#95](https://github.com/poanetwork/metamask-extension/pull/95): (Feature) Support of token per network basis
- [#85](https://github.com/poanetwork/metamask-extension/pull/85): (Upgrade) node, npm packages versions
- [#84](https://github.com/poanetwork/metamask-extension/pull/84): (Fix) Change green color
- [#83](https://github.com/poanetwork/metamask-extension/pull/83), [#92](https://github.com/poanetwork/metamask-extension/pull/92): (Feature) Changing of password
- [#81](https://github.com/poanetwork/metamask-extension/pull/81): (Feature) Deanonymize private network
- [#80](https://github.com/poanetwork/metamask-extension/pull/80): (Feature) Remove imported account
- [#78](https://github.com/poanetwork/metamask-extension/pull/78): (Fix) Link to POA explorer for POA networks

## 4.8.4 Thu Aug 09 2018

- [#70](https://github.com/poanetwork/metamask-extension/pull/70): Change ShapeShift API key
- [#69](https://github.com/poanetwork/metamask-extension/pull/69): Restyling: fix page headers, redesigned warnings, fix paddings, update some icons, redesigned page for buying, redesigned confirm screens, redesigned account menu
- [#67](https://github.com/poanetwork/metamask-extension/pull/67): Improve performance when big list of sent transactions from account
- [#66](https://github.com/poanetwork/metamask-extension/pull/66): Added possibility to remove custom RPC from the list of networks

## 4.8.3 Fri Aug 03 2018

- [#59](https://github.com/poanetwork/metamask-extension/pull/59): Update e2e test of Terms of Use page
- [#58](https://github.com/poanetwork/metamask-extension/pull/58): Update Terms of Use page style
- [#57](https://github.com/poanetwork/metamask-extension/pull/57): Optimized images for release.
- [#55](https://github.com/poanetwork/metamask-extension/pull/55): Tests fix.
- [#52](https://github.com/poanetwork/metamask-extension/pull/52): Nifty Wallet restyling.
- [#54](https://github.com/poanetwork/metamask-extension/pull/54): Fix explorer url for POA network on confirmed transaction.
- [#50](https://github.com/poanetwork/metamask-extension/pull/50): Update sentry links.
- [#45](https://github.com/poanetwork/metamask-extension/pull/45): Automate release publish.
- [#39](https://github.com/poanetwork/metamask-extension/pull/39): Swap npm Jazzicon dependency to Rockicon with changed palette for identicon

## 4.8.2 Thu Jul 26 2018

- Add new tokens auto detection
- Remove rejected transactions from transaction history
- Add Trezor Support
- Allow to remove accounts (Imported and Hardware Wallets)

## 4.8.0 Thur Jun 14 2018

- [#4513](https://github.com/MetaMask/metamask-extension/pull/4513): Attempting to import an empty private key will now show a clear error.
- [#4570](https://github.com/MetaMask/metamask-extension/pull/4570): Fix bug where metamask data would stop being written to disk after prolonged use.
- [#4523](https://github.com/MetaMask/metamask-extension/pull/4523): Fix bug where account reset did not work with custom RPC providers.
- [#4524](https://github.com/MetaMask/metamask-extension/pull/4524): Fix for Brave i18n getAcceptLanguages.
- [#4557](https://github.com/MetaMask/metamask-extension/pull/4557): Fix bug where nonce mutex was never released.
- [#4566](https://github.com/MetaMask/metamask-extension/pull/4566): Add phishing notice.
- [#4591](https://github.com/MetaMask/metamask-extension/pull/4591): Allow Copying Token Addresses and link to Token on Etherscan.

## 4.7.4 Tue Jun 05 2018

- Add diagnostic reporting for users with multiple HD keyrings
- Throw explicit error when selected account is unset

## 4.7.3 Mon Jun 04 2018

- Hide token now uses new modal
- Indicate the current selected account on the popup account view
- Reduce height of notice container in onboarding
- Fixes issue where old nicknames were kept around causing errors

## 4.7.2 Sun Jun 03 2018

- Fix bug preventing users from logging in. Internally accounts and identities were out of sync.
- Fix support links to point to new support system (Zendesk)
- Fix bug in migration #26 ( moving account nicknames to preferences )
- Clears account nicknames on restore from seedPhrase

## 4.7.1 Fri Jun 01 2018

- Fix bug where errors were not returned to Dapps.

## 4.7.0 Wed May 30 2018

- Fix Brave support
- Adds error messages when passwords don't match in onboarding flow.
- Adds modal notification if a retry in the process of being confirmed is dropped.
- New unlock screen design.
- Design improvements to the add token screen.
- Fix inconsistencies in confirm screen between extension and browser window modes.
- Fix scrolling in deposit ether modal.
- Fix styling of app spinner.
- Font weight changed from 300 to 400.
- New reveal screen design.
- Styling improvements to labels in first time flow and signature request headers.

## 4.6.1 Mon Apr 30 2018

- Fix bug where sending a transaction resulted in an infinite spinner
- Allow transactions with a 0 gwei gas price
- Handle encoding errors in ERC20 symbol + digits
- Fix ShapeShift forms (new + old ui)
- Fix sourcemaps

## 4.6.0 Thu Apr 26 2018

- Correctly format currency conversion for locally selected preferred currency.
- Improved performance of 3D fox logo.
- Fetch token prices based on contract address, not symbol
- Fix bug that prevents setting language locale in settings.
- Show checksum addresses throughout the UI
- Allow transactions with a 0 gwei gas price
- Made provider RPC errors contain useful messages

## 4.5.5 Fri Apr 06 2018

- Graceful handling of unknown keys in txParams
- Fixes buggy handling of historical transactions with unknown keys in txParams
- Fix link for 'Learn More' in the Add Token Screen to open to a new tab.
- Fix Download State Logs button [#3791](https://github.com/MetaMask/metamask-extension/issues/3791)
- Enhanced migration error handling + reporting

## 4.5.4 (aborted) Thu Apr 05 2018

- Graceful handling of unknown keys in txParams
- Fix link for 'Learn More' in the Add Token Screen to open to a new tab.
- Fix Download State Logs button [#3791](https://github.com/MetaMask/metamask-extension/issues/3791)
- Fix migration error reporting

## 4.5.3 Wed Apr 04 2018

- Fix bug where checksum address are messing with balance issue [#3843](https://github.com/MetaMask/metamask-extension/issues/3843)
- new ui: fix the confirm transaction screen

## 4.5.2 Wed Apr 04 2018

- Fix overly strict validation where transactions were rejected with hex encoded "chainId"

## 4.5.1 Tue Apr 03 2018

- Fix default network (should be mainnet not Rinkeby)
- Fix Sentry automated error reporting endpoint

## 4.5.0 Mon Apr 02 2018

- (beta ui) Internationalization: Select your preferred language in the settings screen
- Internationalization: various locale improvements
- Fix bug where the "Reset account" feature would not clear the network cache.
- Increase maximum gas limit, to allow very gas heavy transactions, since block gas limits have been stable.

## 4.4.0 Mon Mar 26 2018

- Internationalization: Taiwanese, Thai, Slovenian
- Fixes bug where MetaMask would not open once its storage grew too large.
- Updates design of new-ui Add Token screen
- New-ui can send to ens addresses
- Update new-ui button styles
- Signed-type-data notification handles long messages
- Popup extension in new-ui uses new on-boarding designs
- Buy ether step of new-ui on-boarding uses new buy ether modal designs

## 4.3.0 Wed Mar 21 2018

- (beta) Add internationalization support! Includes translations for 13 (!!) new languages: French, Spanish, Italian, German, Dutch, Portuguese, Japanese, Korean, Vietnamese, Mandarin, Hindi, Tagalog, and Russian! Select "Try Beta" in the menu to take them for a spin. Read more about the community effort [here](https://medium.com/gitcoin/metamask-internationalizes-via-gitcoin-bf1390c0301c)
- No longer uses nonces specified by the dapp
- Will now throw an error if the `to` field in txParams is not valid.
- Will strip null values from the `to` field.
- (beta) No longer shows token confirmation screen when performing a non-send
- (beta) Fixes bug where tx data was nullified when repricing a tx
- Fix flashing Login screen after logging in or restoring from seed phrase.
- Increase tap areas for menu buttons on mobile
- Change all fonts in new-ui onboarding to Roboto, size 400
- Add a welcome screen to new-ui onboarding flow
- Make new-ui create password screen responsive
- Hide network dropdown before account is initialized
- Fix bug that could prevent MetaMask from saving the latest vault.

## 4.2.0 Tue Mar 06 2018

- Replace "Loose" wording to "Imported".
- Replace "Unlock" wording with "Log In".
- Add Imported Account disclaimer.
- Allow adding custom tokens to classic ui when balance is 0
- Allow editing of symbol and decimal info when adding custom token in new-ui
- NewUI shapeshift form can select all coins (not just BTC)
- Add most of Microsoft Edge support.

## 4.1.3 2018-2-28

- Ensure MetaMask's inpage provider is named MetamaskInpageProvider to keep some sites from breaking.
- Add retry transaction button back into classic ui.
- Add network dropdown styles to support long custom RPC urls

## 4.1.2 2018-2-28

- Actually includes all the fixes mentioned in 4.1.1 (sorry)

## 4.1.1 2018-2-28

- Fix "Add Token" screen referencing missing token logo urls
- Prevent user from switching network during signature request
- Fix misleading language "Contract Published" -> "Contract Deployment"
- Fix cancel button on "Buy Eth" screen
- Improve new-ui onboarding flow style

## 4.1.0 2018-2-27

- Report failed txs to Sentry with more specific message
- Fix internal feature flags being sometimes undefined
- Standardized license to MIT

## 4.0.0 2018-2-22

- Introduce new MetaMask user interface.

## 3.14.2 2018-2-15

- Fix bug where log subscriptions would break when switching network.
- Fix bug where storage values were cached across blocks.
- Add MetaMask light client [testing container](https://github.com/MetaMask/mesh-testing)

## 3.14.1 2018-2-1

- Further fix scrolling for Firefox.

## 3.14.0 2018-2-1

- Removed unneeded data from storage
- Add a "reset account" feature to Settings
- Add warning for importing some kinds of files.
- Scrollable Setting view for Firefox.

## 3.13.8 2018-1-29

- Fix provider for Kovan network.
- Bump limit for EventEmitter listeners before warning.
- Display Error when empty string is entered as a token address.

## 3.13.7 2018-1-22

- Add ability to bypass gas estimation loading indicator.
- Forward failed transactions to Sentry error reporting service
- Re-add changes from 3.13.5

## 3.13.6 2017-1-18

- Roll back changes to 3.13.4 to fix some issues with the new Infura REST provider.

## 3.13.5 2018-1-16

- Estimating gas limit for simple ether sends now faster & cheaper, by avoiding VM usage on recipients with no code.
- Add an extra px to address for Firefox clipping.
- Fix Firefox scrollbar.
- Open metamask popup for transaction confirmation before gas estimation finishes and add a loading screen over transaction confirmation.
- Fix bug that prevented eth_signTypedData from signing bytes.
- Further improve gas price estimation.

## 3.13.4 2018-1-9

- Remove recipient field if application initializes a tx with an empty string, or 0x, and tx data. Throw an error with the same condition, but without tx data.
- Improve gas price suggestion to be closer to the lowest that will be accepted.
- Throw an error if a application tries to submit a tx whose value is a decimal, and inform that it should be in wei.
- Fix bug that prevented updating custom token details.
- No longer mark long-pending transactions as failed, since we now have button to retry with higher gas.
- Fix rounding error when specifying an ether amount that has too much precision.
- Fix bug where incorrectly inputting seed phrase would prevent any future attempts from succeeding.

## 3.13.3 2017-12-14

- Show tokens that are held that have no balance.
- Reduce load on Infura by using a new block polling endpoint.

## 3.13.2 2017-12-9

- Reduce new block polling interval to 8000 ms, to ease server load.

## 3.13.1 2017-12-7

- Allow Dapps to specify a transaction nonce, allowing dapps to propose resubmit and force-cancel transactions.

## 3.13.0 2017-12-7

- Allow resubmitting transactions that are taking long to complete.

## 3.12.1 2017-11-29

- Fix bug where a user could be shown two different seed phrases.
- Detect when multiple web3 extensions are active, and provide useful error.
- Adds notice about seed phrase backup.

## 3.12.0 2017-10-25

- Add support for alternative ENS TLDs (Ethereum Name Service Top-Level Domains).
- Lower minimum gas price to 0.1 GWEI.
- Remove web3 injection message from production (thanks to @ChainsawBaby)
- Add additional debugging info to our state logs, specifically OS version and browser version.

## 3.11.2 2017-10-21

- Fix bug where reject button would sometimes not work.
- Fixed bug where sometimes MetaMask's connection to a page would be unreliable.

## 3.11.1 2017-10-20

- Fix bug where log filters were not populated correctly
- Fix bug where web3 API was sometimes injected after the page loaded.
- Fix bug where first account was sometimes not selected correctly after creating or restoring a vault.
- Fix bug where imported accounts could not use new eth_signTypedData method.

## 3.11.0 2017-10-11

- Add support for new eth_signTypedData method per EIP 712.
- Fix bug where some transactions would be shown as pending forever, even after successfully mined.
- Fix bug where a transaction might be shown as pending forever if another tx with the same nonce was mined.
- Fix link to support article on token addresses.

## 3.10.9 2017-10-5

- Only rebrodcast transactions for a day not a days worth of blocks
- Remove Slack link from info page, since it is a big phishing target.
- Stop computing balance based on pending transactions, to avoid edge case where users are unable to send transactions.

## 3.10.8 2017-9-28

- Fixed usage of new currency fetching API.

## 3.10.7 2017-9-28

- Fixed bug where sometimes the current account was not correctly set and exposed to web apps.
- Added AUD, HKD, SGD, IDR, PHP to currency conversion list

## 3.10.6 2017-9-27

- Fix bug where newly created accounts were not selected.
- Fix bug where selected account was not persisted between lockings.

## 3.10.5 2017-9-27

- Fix block gas limit estimation.

## 3.10.4 2017-9-27

- Fix bug that could mis-render token balances when very small. (Not actually included in 3.9.9)
- Fix memory leak warning.
- Fix bug where new event filters would not include historical events.

## 3.10.3 2017-9-21

- Fix bug where metamask-dapp connections are lost on rpc error
- Fix bug that would sometimes display transactions as failed that could be successfully mined.

## 3.10.2 2017-9-18

rollback to 3.10.0 due to bug

## 3.10.1 2017-9-18

- Add ability to export private keys as a file.
- Add ability to export seed words as a file.
- Changed state logs to a file download than a clipboard copy.
- Add specific error for failed recipient address checksum.
- Fixed a long standing memory leak associated with filters installed by dapps
- Fix link to support center.
- Fixed tooltip icon locations to avoid overflow.
- Warn users when a dapp proposes a high gas limit (90% of blockGasLimit or higher
- Sort currencies by currency name (thanks to strelok1: https://github.com/strelok1).

## 3.10.0 2017-9-11

- Readded loose keyring label back into the account list.
- Remove cryptonator from chrome permissions.
- Add info on token contract addresses.
- Add validation preventing users from inputting their own addresses as token tracking addresses.
- Added button to reject all transactions (thanks to davidp94! https://github.com/davidp94)


## 3.9.13 2017-9-8

- Changed the way we initialize the inpage provider to fix a bug affecting some developers.

## 3.9.12 2017-9-6

- Fix bug that prevented Web3 1.0 compatibility
- Make eth_sign deprecation warning less noisy
- Add useful link to eth_sign deprecation warning.
- Fix bug with network version serialization over synchronous RPC
- Add MetaMask version to state logs.
- Add the total amount of tokens when multiple tokens are added under the token list
- Use HTTPS links for Etherscan.
- Update Support center link to new one with HTTPS.
- Make web3 deprecation notice more useful by linking to a descriptive article.

## 3.9.11 2017-8-24

- Fix nonce calculation bug that would sometimes generate very wrong nonces.
- Give up resubmitting a transaction after 3500 blocks.

## 3.9.10 2017-8-23

- Improve nonce calculation, to prevent bug where people are unable to send transactions reliably.
- Remove link to eth-tx-viz from identicons in tx history.

## 3.9.9 2017-8-18

- Fix bug where some transaction submission errors would show an empty screen.
- Fix bug that could mis-render token balances when very small.
- Fix formatting of eth_sign "Sign Message" view.
- Add deprecation warning to eth_sign "Sign Message" view.

## 3.9.8 2017-8-16

- Reenable token list.
- Remove default tokens.

## 3.9.7 2017-8-15

- hotfix - disable token list
- Added a deprecation warning for web3 https://github.com/ethereum/mist/releases/tag/v0.9.0

## 3.9.6 2017-8-09

- Replace account screen with an account drop-down menu.
- Replace account buttons with a new account-specific drop-down menu.

## 3.9.5 2017-8-04

- Improved phishing detection configuration update rate

## 3.9.4 2017-8-03

- Fixed bug that prevented transactions from being rejected.

## 3.9.3 2017-8-03

- Add support for EGO ujo token
- Continuously update blacklist for known phishing sites in background.
- Automatically detect suspicious URLs too similar to common phishing targets, and blacklist them.

## 3.9.2 2017-7-26

- Fix bugs that could sometimes result in failed transactions after switching networks.
- Include stack traces in txMeta's to better understand the life cycle of transactions
- Enhance blacklister functionality to include levenshtein logic. (credit to @sogoiii and @409H for their help!)

## 3.9.1 2017-7-19

- No longer automatically request 1 ropsten ether for the first account in a new vault.
- Now redirects from known malicious sites faster.
- Added a link to our new support page to the help screen.
- Fixed bug where a new transaction would be shown over the current transaction, creating a possible timing attack against user confirmation.
- Fixed bug in nonce tracker where an incorrect nonce would be calculated.
- Lowered minimum gas price to 1 Gwei.

## 3.9.0 2017-7-12

- Now detects and blocks known phishing sites.

## 3.8.6 2017-7-11

- Make transaction resubmission more resilient.
- No longer validate nonce client-side in retry loop.
- Fix bug where insufficient balance error was sometimes shown on successful transactions.

## 3.8.5 2017-7-7

- Fix transaction resubmit logic to fail slightly less eagerly.

## 3.8.4 2017-7-7

- Improve transaction resubmit logic to fail more eagerly when a user would expect it to.

## 3.8.3 2017-7-6

- Re-enable default token list.
- Add origin header to dapp-bound requests to allow providers to throttle sites.
- Fix bug that could sometimes resubmit a transaction that had been stalled due to low balance after balance was restored.

## 3.8.2 2017-7-3

- No longer show network loading indication on config screen, to allow selecting custom RPCs.
- Visually indicate that network spinner is a menu.
- Indicate what network is being searched for when disconnected.

## 3.8.1 2017-6-30

- Temporarily disabled loading popular tokens by default to improve performance.
- Remove SEND token button until a better token sending form can be built, due to some precision issues.
- Fix precision bug in token balances.
- Cache token symbol and precisions to reduce network load.
- Transpile some newer JavaScript, restores compatibility with some older browsers.

## 3.8.0 2017-6-28

- No longer stop rebroadcasting transactions
- Add list of popular tokens held to the account detail view.
- Add ability to add Tokens to token list.
- Add a warning to JSON file import.
- Add "send" link to token list, which goes to TokenFactory.
- Fix bug where slowly mined txs would sometimes be incorrectly marked as failed.
- Fix bug where badge count did not reflect personal_sign pending messages.
- Seed word confirmation wording is now scarier.
- Fix error for invalid seed words.
- Prevent users from submitting two duplicate transactions by disabling submit.
- Allow Dapps to specify gas price as hex string.
- Add button for copying state logs to clipboard.

## 3.7.8 2017-6-12

- Add an `ethereum:` prefix to the QR code address
- The default network on installation is now MainNet
- Fix currency API URL from cryptonator.
- Update gasLimit params with every new block seen.
- Fix ENS resolver symbol UI.

## 3.7.7 2017-6-8

- Fix bug where metamask would show old data after computer being asleep or disconnected from the internet.

## 3.7.6 2017-6-5

- Fix bug that prevented publishing contracts.

## 3.7.5 2017-6-5

- Prevent users from sending to the `0x0` address.
- Provide useful errors when entering bad characters in ENS name.
- Add ability to copy addresses from transaction confirmation view.

## 3.7.4 2017-6-2

- Fix bug with inflight cache that caused some block lookups to return bad values (affected OasisDex).
- Fixed bug with gas limit calculation that would sometimes create unsubmittable gas limits.

## 3.7.3 2017-6-1

- Rebuilt to fix cache clearing bug.

## 3.7.2 2017-5-31

- Now when switching networks sites that use web3 will reload
- Now when switching networks the extension does not restart
- Cleanup decimal bugs in our gas inputs.
- Fix bug where submit button was enabled for invalid gas inputs.
- Now enforce 95% of block's gasLimit to protect users.
- Removing provider-engine from the inpage provider. This fixes some error handling inconsistencies introduced in 3.7.0.
- Added "inflight cache", which prevents identical requests from clogging up the network, dramatically improving ENS performance.
- Fixed bug where filter subscriptions would sometimes fail to unsubscribe.
- Some contracts will now display logos instead of jazzicons.
- Some contracts will now have names displayed in the confirmation view.

## 3.7.0 2017-5-23

- Add Transaction Number (nonce) to transaction list.
- Label the pending tx icon with a tooltip.
- Fix bug where website filters would pile up and not deallocate when leaving a site.
- Continually resubmit pending txs for a period of time to ensure successful broadcast.
- ENS names will no longer resolve to their owner if no resolver is set. Resolvers must be explicitly set and configured.

## 3.6.5 2017-5-17

- Fix bug where edited gas parameters would not take effect.
- Trim currency list.
- Enable decimals in our gas prices.
- Fix reset button.
- Fix event filter bug introduced by newer versions of Geth.
- Fix bug where decimals in gas inputs could result in strange values.

## 3.6.4 2017-5-8

- Fix main-net ENS resolution.

## 3.6.3 2017-5-8

- Fix bug that could stop newer versions of Geth from working with MetaMask.

## 3.6.2 2017-5-8

- Input gas price in Gwei.
- Enforce Safe Gas Minimum recommended by EthGasStation.
- Fix bug where block-tracker could stop polling for new blocks.
- Reduce UI size by removing internal web3.
- Fix bug where gas parameters would not properly update on adjustment.

## 3.6.1 2017-4-30

- Made fox less nosy.
- Fix bug where error was reported in debugger console when Chrome opened a new window.

## 3.6.0 2017-4-26

- Add Rinkeby Test Network to our network list.

## 3.5.4 2017-4-25

- Fix occasional nonce tracking issue.
- Fix bug where some events would not be emitted by web3.
- Fix bug where an error would be thrown when composing signatures for networks with large ID values.

## 3.5.3 2017-4-24

- Popup new transactions in Firefox.
- Fix transition issue from account detail screen.
- Revise buy screen for more modularity.
- Fixed some other small bugs.

## 3.5.2 2017-3-28

- Fix bug where gas estimate totals were sometimes wrong.
- Add link to Kovan Test Faucet instructions on buy view.
- Inject web3 into loaded iFrames.

## 3.5.1 2017-3-27

- Fix edge case where users were unable to enable the notice button if notices were short enough to not require a scrollbar.

## 3.5.0 2017-3-27

- Add better error messages for when a transaction fails on approval
- Allow sending to ENS names in send form on Ropsten.
- Added an address book functionality that remembers the last 15 unique addresses sent to.
- Can now change network to custom RPC URL from lock screen.
- Removed support for old, lightwallet based vault. Users who have not opened app in over a month will need to recover with their seed phrase. This will allow Firefox support sooner.
- Fixed bug where spinner wouldn't disappear on incorrect password submission on seed word reveal.
- Polish the private key UI.
- Enforce minimum values for gas price and gas limit.
- Fix bug where total gas was sometimes not live-updated.
- Fix bug where editing gas value could have some abrupt behaviors (#1233)
- Add Kovan as an option on our network list.
- Fixed bug where transactions on other networks would disappear when submitting a transaction on another network.

## 3.4.0 2017-3-8

- Add two most recently used custom RPCs to network dropdown menu.
- Add personal_sign method support.
- Add personal_ecRecover method support.
- Add ability to customize gas and gasPrice on the transaction approval screen.
- Increase default gas buffer to 1.5x estimated gas value.

## 3.3.0 2017-2-20

- net_version has been made synchronous.
- Test suite for migrations expanded.
- Network now changeable from lock screen.
- Improve test coverage of eth.sign behavior, including a code example of verifying a signature.

## 3.2.2 2017-2-8

- Revert eth.sign behavior to the previous one with a big warning.  We will be gradually implementing the new behavior over the coming time. https://github.com/ethereum/wiki/wiki/JSON-RPC#eth_sign

- Improve test coverage of eth.sign behavior, including a code example of verifying a signature.

## 3.2.2 2017-2-8

- Revert eth.sign behavior to the previous one with a big warning.  We will be gradually implementing the new behavior over the coming time. https://github.com/ethereum/wiki/wiki/JSON-RPC#eth_sign

## 3.2.1 2017-2-8

- Revert back to old style message signing.
- Fixed some build errors that were causing a variety of bugs.

## 3.2.0 2017-2-8

- Add ability to import accounts in JSON file format (used by Mist, Geth, MyEtherWallet, and more!)
- Fix unapproved messages not being included in extension badge.
- Fix rendering bug where the Confirm transaction view would let you approve transactions when the account has insufficient balance.

## 3.1.2 2017-1-24

- Fix "New Account" default keychain

## 3.1.1 2017-1-20

- Fix HD wallet seed export

## 3.1.0 2017-1-18

- Add ability to import accounts by private key.
- Fixed bug that returned the wrong transaction hashes on private networks that had not implemented EIP 155 replay protection (like TestRPC).

## 3.0.1 2017-1-17

- Fixed bug that prevented eth.sign from working.
- Fix the displaying of transactions that have been submitted to the network in Transaction History

## 3.0.0 2017-1-16

- Fix seed word account generation (https://medium.com/metamask/metamask-3-migration-guide-914b79533cdd#.t4i1qmmsz).
- Fix Bug where you see an empty transaction flash by on the confirm transaction view.
- Create visible difference in transaction history between an approved but not yet included in a block transaction and a transaction who has been confirmed.
- Fix memory leak in RPC Cache
- Override RPC commands eth_syncing and web3_clientVersion
- Remove certain non-essential permissions from certain builds.
- Add a check for when a tx is included in a block.
- Fix bug where browser-solidity would sometimes warn of a contract creation error when there was none.
- Minor modifications to network display.
- Network now displays properly for pending transactions.
- Implement replay attack protections allowed by EIP 155.
- Fix bug where sometimes loading account data would fail by querying a future block.

## 2.14.1 2016-12-20

- Update Coinbase info. and increase the buy amount to $15
- Fixed ropsten transaction links
- Temporarily disable extension reload detection causing infinite reload bug.
- Implemented basic checking for valid RPC URIs.

## 2.14.0 2016-12-16

- Removed Morden testnet provider from provider menu.
- Add support for notices.
- Fix broken reload detection.
- Fix transaction forever cached-as-pending bug.

## 2.13.11 2016-11-23

- Add support for synchronous RPC method "eth_uninstallFilter".
- Forgotten password prompts now send users directly to seed word restoration.

## 2.13.10 2016-11-22

- Improve gas calculation logic.
- Default to Dapp-specified gas limits for transactions.
- Ropsten networks now properly point to the faucet when attempting to buy ether.
- Ropsten transactions now link to etherscan correctly.

## 2.13.9 2016-11-21

- Add support for the new, default Ropsten Test Network.
- Fix bug that would cause MetaMask to occasionally lose its StreamProvider connection and drop requests.
- Fix bug that would cause the Custom RPC menu item to not appear when Localhost 8545 was selected.
- Point ropsten faucet button to actual faucet.
- Phase out ethereumjs-util from our encryptor module.

## 2.13.8 2016-11-16

- Show a warning when a transaction fails during simulation.
- Fix bug where 20% of gas estimate was not being added properly.
- Render error messages in confirmation screen more gracefully.

## 2.13.7 2016-11-8

- Fix bug where gas estimate would sometimes be very high.
- Increased our gas estimate from 100k gas to 20% of estimate.
- Fix GitHub link on info page to point at current repository.

## 2.13.6 2016-10-26

- Add a check for improper Transaction data.
- Inject up to date version of web3.js
- Now nicknaming new accounts "Account #" instead of "Wallet #" for clarity.
- Fix bug where custom provider selection could show duplicate items.
- Fix bug where connecting to a local morden node would make two providers appear selected.
- Fix bug that was sometimes preventing transactions from being sent.

## 2.13.5 2016-10-18

- Increase default max gas to `100000` over the RPC's `estimateGas` response.
- Fix bug where slow-loading dapps would sometimes trigger infinite reload loops.

## 2.13.4 2016-10-17

- Add custom transaction fee field to send form.
- Fix bug where web3 was being injected into XML files.
- Fix bug where changing network would not reload current Dapps.

## 2.13.3 2016-10-4

- Fix bug where log queries were filtered out.
- Decreased vault confirmation button font size to help some Linux users who could not see it.
- Made popup a little taller because it would sometimes cut off buttons.
- Fix bug where long account lists would get scrunched instead of scrolling.
- Add legal information to relevant pages.
- Rename UI elements to be more consistent with one another.
- Updated Terms of Service and Usage.
- Prompt users to re-agree to the Terms of Service when they are updated.

## 2.13.2 2016-10-4

- Fix bug where chosen FIAT exchange rate does no persist when switching networks
- Fix additional parameters that made MetaMask sometimes receive errors from Parity.
- Fix bug where invalid transactions would still open the MetaMask popup.
- Removed hex prefix from private key export, to increase compatibility with Geth, MyEtherWallet, and Jaxx.

## 2.13.1 2016-09-23

- Fix a bug with estimating gas on Parity
- Show loading indication when selecting ShapeShift as purchasing method.

## 2.13.0 2016-09-18

- Add Parity compatibility, fixing Geth dependency issues.
- Add a link to the transaction in history that goes to https://metamask.github.io/eth-tx-viz
too help visualize transactions and to where they are going.
- Show "Buy Ether" button and warning on tx confirmation when sender balance is insufficient

## 2.12.1 2016-09-14

- Fixed bug where if you send a transaction from within MetaMask extension the
popup notification opens up.
- Fixed bug where some tx errors would block subsequent txs until the plugin was refreshed.

## 2.12.0 2016-09-14

- Add a QR button to the Account detail screen
- Fixed bug where opening MetaMask could close a non-metamask popup.
- Fixed memory leak that caused occasional crashes.

## 2.11.1 2016-09-12

- Fix bug that prevented caches from being cleared in Opera.

## 2.11.0 2016-09-12

- Fix bug where pending transactions from Test net (or other networks) show up In Main net.
- Add fiat conversion values to more views.
- On fresh install, open a new tab with the MetaMask Introduction video. Does not open on update.
- Block negative values from transactions.
- Fixed a memory leak.
- MetaMask logo now renders as super lightweight SVG, improving compatibility and performance.
- Now showing loading indication during vault unlocking, to clarify behavior for users who are experiencing slow unlocks.
- Now only initially creates one wallet when restoring a vault, to reduce some users' confusion.

## 2.10.2 2016-09-02

- Fix bug where notification popup would not display.

## 2.10.1 2016-09-02

- Fix bug where provider menu did not allow switching to custom network from a custom network.
- Sending a transaction from within MetaMask no longer triggers a popup.
- The ability to build without livereload features (such as for production) can be enabled with the gulp --disableLiveReload flag.
- Fix Ethereum JSON RPC Filters bug.

## 2.10.0 2016-08-29

- Changed transaction approval from notifications system to popup system.
- Add a back button to locked screen to allow restoring vault from seed words when password is forgotten.
- Forms now retain their values even when closing the popup and reopening it.
- Fixed a spelling error in provider menu.

## 2.9.2 2016-08-24

- Fixed shortcut bug from preventing installation.

## 2.9.1 2016-08-24

- Added static image as fallback for when WebGL isn't supported.
- Transaction history now has a hard limit.
- Added info link on account screen that visits Etherscan.
- Fixed bug where a message signing request would be lost if the vault was locked.
- Added shortcut to open MetaMask (Ctrl+Alt+M or Cmd+Opt/Alt+M)
- Prevent API calls in tests.
- Fixed bug where sign message confirmation would sometimes render blank.

## 2.9.0 2016-08-22

- Added ShapeShift to the transaction history
- Added affiliate key to Shapeshift requests
- Added feature to reflect current conversion rates of current vault balance.
- Modify balance display logic.

## 2.8.0 2016-08-15

- Integrate ShapeShift
- Add a form for Coinbase to specify amount to buy
- Fix various typos.
- Make dapp-metamask connection more reliable
- Remove Ethereum Classic from provider menu.

## 2.7.3 2016-07-29

- Fix bug where changing an account would not update in a live Dapp.

## 2.7.2 2016-07-29

- Add Ethereum Classic to provider menu
- Fix bug where host store would fail to receive updates.

## 2.7.1 2016-07-27

- Fix bug where web3 would sometimes not be injected in time for the application.
- Fixed bug where sometimes when opening the plugin, it would not fully open until closing and re-opening.
- Got most functionality working within Firefox (still working on review process before it can be available).
- Fixed menu dropdown bug introduced in Chrome 52.

## 2.7.0 2016-07-21

- Added a Warning screen about storing ETH
- Add buy Button!
- MetaMask now throws descriptive errors when apps try to use synchronous web3 methods.
- Removed firefox-specific line in manifest.

## 2.6.2 2016-07-20

- Fixed bug that would prevent the plugin from reopening on the first try after receiving a new transaction while locked.
- Fixed bug that would render 0 ETH as a non-exact amount.

## 2.6.1 2016-07-13

- Fix tool tips on Eth balance to show the 6 decimals
- Fix rendering of recipient SVG in tx approval notification.
- New vaults now generate only one wallet instead of three.
- Bumped version of web3 provider engine.
- Fixed bug where some lowercase or uppercase addresses were not being recognized as valid.
- Fixed bug where gas cost was misestimated on the tx confirmation view.

## 2.6.0 2016-07-11

- Fix formatting of ETH balance
- Fix formatting of account details.
- Use web3 minified dist for faster inject times
- Fix issue where dropdowns were not in front of icons.
- Update transaction approval styles.
- Align failed and successful transaction history text.
- Fix issue where large domain names and large transaction values would misalign the transaction history.
- Abbreviate ether balances on transaction details to maintain formatting.
- General code cleanup.

## 2.5.0 2016-06-29

- Implement new account design.
- Added a network indicator mark in dropdown menu
- Added network name next to network indicator
- Add copy transaction hash button to completed transaction list items.
- Unify wording for transaction approve/reject options on notifications and the extension.
- Fix bug where confirmation view would be shown twice.

## 2.4.5 2016-06-29

- Fixed bug where MetaMask interfered with PDF loading.
- Moved switch account icon into menu bar.
- Changed status shapes to be a yellow warning sign for failure and ellipsis for pending transactions.
- Now enforce 20 character limit on wallet names.
- Wallet titles are now properly truncated in transaction confirmation.
- Fix formatting on terms & conditions page.
- Now enforce 30 character limit on wallet names.
- Fix out-of-place positioning of pending transaction badges on wallet list.
- Change network status icons to reflect current design.

## 2.4.4 2016-06-23

- Update web3-stream-provider for batch payload bug fix

## 2.4.3 2016-06-23

- Remove redundant network option buttons from settings page
- Switch out font family Transat for Montserrat

## 2.4.2 2016-06-22

- Change out export icon for key.
- Unify copy to clipboard icon
- Fixed eth.sign behavior.
- Fix behavior of batched outbound transactions.

## 2.4.0 2016-06-20

- Clean up UI.
- Remove nonfunctional QR code button.
- Make network loading indicator clickable to select accessible network.
- Show more characters of addresses when space permits.
- Fixed bug when signing messages under 64 hex characters long.
- Add disclaimer view with placeholder text for first time users.

## 2.3.1 2016-06-09

- Style up the info page
- Cache identicon images to optimize for long lists of transactions.
- Fix out of gas errors

## 2.3.0 2016-06-06

- Show network status in title bar
- Added seed word recovery to config screen.
- Clicking network status indicator now reveals a provider menu.

## 2.2.0 2016-06-02

- Redesigned init, vault create, vault restore and seed confirmation screens.
- Added pending transactions to transaction list on account screen.
- Clicking a pending transaction takes you back to the transaction approval screen.
- Update provider-engine to fix intermittent out of gas errors.

## 2.1.0 2016-05-26

- Added copy address button to account list.
- Fixed back button on confirm transaction screen.
- Add indication of pending transactions to account list screen.
- Fixed bug where error warning was sometimes not cleared on view transition.
- Updated eth-lightwallet to fix a critical security issue.

## 2.0.0 2016-05-23

- UI Overhaul per Vlad Todirut's designs.
- Replaced identicons with jazzicons.
- Fixed glitchy transitions.
- Added support for capitalization-based address checksums.
- Send value is no longer limited by javascript number precision, and is always in ETH.
- Added ability to generate new accounts.
- Added ability to locally nickname accounts.

## 1.8.4 2016-05-13

- Point rpc servers to https endpoints.

## 1.8.3 2016-05-12

- Bumped web3 to 0.6.0
- Really fixed `eth_syncing` method response.

## 1.8.2 2016-05-11

- Fixed bug where send view would not load correctly the first time it was visited per account.
- Migrated all users to new scalable backend.
- Fixed `eth_syncing` method response.

## 1.8.1 2016-05-10

- Initial usage of scalable blockchain backend.
- Made official providers more easily configurable for us internally.

## 1.8.0 2016-05-10

- Add support for calls to `eth.sign`.
- Moved account exporting within subview of the account detail view.
- Added buttons to the account export process.
- Improved visual appearance of account detail transition where button heights would change.
- Restored back button to account detail view.
- Show transaction list always, never collapsed.
- Changing provider now reloads current Dapps
- Improved appearance of transaction list in account detail view.

## 1.7.0 2016-04-29

- Account detail view is now the primary view.
- The account detail view now has a "Change acct" button which shows the account list.
- Clicking accounts in the account list now both selects that account and displays that account's detail view.
- Selected account is now persisted between sessions, so the current account stays selected.
- Account icons are now "identicons" (deterministically generated from the address).
- Fixed link to Slack channel.
- Added a context guard for "define" to avoid UMD's exporting themselves to the wrong module system, fixing interference with some websites.
- Transaction list now only shows transactions for the current account.
- Transaction list now only shows transactions for the current network (mainnet, testnet, testrpc).
- Fixed transaction links to etherscan blockchain explorer.
- Fixed some UI transitions that had weird behavior.

## 1.6.0 2016-04-22

- Pending transactions are now persisted to localStorage and resume even after browser is closed.
- Completed transactions are now persisted and can be displayed via UI.
- Added transaction list to account detail view.
- Fix bug on config screen where current RPC address was always displayed wrong.
- Fixed bug where entering a decimal value when sending a transaction would result in sending the wrong amount.
- Add save button to custom RPC input field.
- Add quick-select button for RPC on `localhost:8545`.
- Improve config view styling.
- Users have been migrated from old test-net RPC to a newer test-net RPC.

## 1.5.1 2016-04-15

- Corrected text above account list. Selected account is visible to all sites, not just the current domain.
- Merged the UI codebase into the main plugin codebase for simpler maintenance.
- Fix Ether display rounding error. Now rendering to four decimal points.
- Fix some inpage synchronous methods
- Change account rendering to show four decimals and a leading zero.

## 1.5.0 2016-04-13

- Added ability to send ether.
- Fixed bugs related to using Javascript numbers, which lacked appropriate precision.
- Replaced Etherscan main-net provider with our own production RPC.

## 1.4.0 2016-04-08

- Removed extra entropy text field for simplified vault creation.
- Now supports exporting an account's private key.
- Unified button and input styles across the app.
- Removed some non-working placeholder UI until it works.
- Fix popup's web3 stream provider
- Temporarily deactivated fauceting indication because it would activate when restoring an empty account.

## 1.3.2 2016-04-04

 - When unlocking, first account is auto-selected.
 - When creating a first vault on the test-net, the first account is auto-funded.
 - Fixed some styling issues.

## 1.0.1-1.3.1

Many changes not logged. Hopefully beginning to log consistently now!

## 1.0.0

Made seed word restoring BIP44 compatible.

## 0.14.0

Added the ability to restore accounts from seed words.
