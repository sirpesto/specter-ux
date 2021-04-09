# Specter UX: Initial State

## Definition

multi-wallet, multi-device coordination tool
All the setups / configurations, one interface: your personal perspective (of ownership) of the bitcoin network
Difference to Electrum: single wallet, multi-device interface

## Genereal Problems

UX is complementary to sercurity (never lose your funds)
No back buttons in multi-step processes
path dependence > setup needs ideally hardware device(s), recommendations?
Team is answering questions directly but they are not preventing the same problem to appear again, learn problem, learning with the tool at hand, where are the resources or are they already embedded in the product itself?

## Initial State

### Add new wallet

"Select the type of the wallet" bad headline
"Adding a wallet with existing funds?" has to go below the options of creating a new one.

Tooltip describes steps that are not relevant to the current page / action:
"Importing an existing wallet?
After choosing device(s), click continue, then just select the:
"Scan for existing funds" checkbox on the next screen."

why asking in the first place? if one device = single-sig, if multiple device = multi-sig
general UX flow: are or should devices already configured?

"Multisig is better for larg-ish amounts." 
- subjective
- trade-offs (https://github.com/cryptoadvance/specter-desktop/blob/master/docs/multisig-security-tradeoffs.md)
- requirements, existing hardware?
- where or how do people learn about their individual setup configuration?

### Import wallet

"Enter your wallet data here" > what exactly do i enter here? where do i find the information for example in electrum?

- electrum file? "Unsupported wallet import format: Expecting value: line 1 column 1 (char 0)"

- see also: https://github.com/cryptoadvance/specter-desktop/issues/570#issuecomment-720233487
  what is with "never typ your keys into software"?

  

## README proposals

- [Verifying Releases](https://github.com/cryptoadvance/specter-desktop/discussions/993#discussioncomment-428335)
- How to contribute / where to look first?
- [How to update](https://github.com/cryptoadvance/specter-desktop/discussions/909) (scared to lose files / funds)
- [Setup guides](https://github.com/cryptoadvance/specter-desktop/discussions/857) (Full Node differences, local, remote, [remote over tor](https://github.com/cryptoadvance/specter-desktop/issues/604#issuecomment-728144342))



## Future Features

- [transaction / utxo labeling](https://github.com/cryptoadvance/specter-desktop/issues/826)
- [adding accounts](https://github.com/cryptoadvance/specter-desktop/issues/881) 

- hide balances / addresses, incognito mode for faster visual debugging when sharing screenshots
- [switch nodes or from mainnet to testnet](https://github.com/cryptoadvance/specter-desktop/issues/28)
- dashboard: node stats + wallet overview / summary 

