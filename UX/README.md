# Specter UX

## Definition

Reviewing the current software development and workspace of [Specter Desktop](https://github.com/cryptoadvance/specter-desktop) \(v1.3.0\).

multi-wallet, multi-device coordination tool All the setups / configurations, one interface: your personal perspective \(of ownership\) of the bitcoin network Difference to Electrum: single wallet, multi-device interface

## General Problems

UX is complementary to security \("never lose your funds"\) Incomplete navigation: no back buttons in multi-step processes setup needs hardware device\(s\), path dependent and therefore preparation or no immediate start possible Team is answering questions directly but they are not preventing the same problem to appear again, learn problem, learning with the tool at hand, where are the resources or are they already embedded in the product itself? Specter is probably a security upgrade to existing bitcoin solutions. Assist the transitions. Repository Readme is rather technical and developer focused. Where are the resources for users? The [FAQ](https://github.com/cryptoadvance/specter-desktop/blob/master/docs/faq.md) / knowledge base is hidden at the end. Splitting FAQ into dev \(technical, documentation\) and user \(guides, best-practices\)? Partially done with [DEVELOPMENT.md](https://github.com/cryptoadvance/specter-desktop/blob/master/DEVELOPMENT.md).

## Initial State

### Add new wallet

"Select the type of the wallet" bad headline "Adding a wallet with existing funds?" has to go below the options of creating a new one.

Tooltip describes steps that are not relevant to the current page / action: "Importing an existing wallet? After choosing device\(s\), click continue, then just select the: "Scan for existing funds" checkbox on the next screen."

why asking in the first place? if one device = single-sig, if multiple device = multi-sig general UX flow: are or should devices already configured?

"Multisig is better for larg-ish amounts."

* subjective
* [trade-offs](https://github.com/cryptoadvance/specter-desktop/blob/master/docs/multisig-security-tradeoffs.md)
* requirements, existing hardware?
* where or how do people learn about their individual setup configuration?

### Import wallet

"Enter your wallet data here" &gt; what exactly do i enter here? where do i find the information for example in electrum?

* electrum file? "Unsupported wallet import format: Expecting value: line 1 column 1 \(char 0\)"
* see also: [https://github.com/cryptoadvance/specter-desktop/issues/570\#issuecomment-720233487](https://github.com/cryptoadvance/specter-desktop/issues/570#issuecomment-720233487) what is with "never typ your keys into software"?

## README proposals

* [Verifying Releases](https://github.com/cryptoadvance/specter-desktop/discussions/993#discussioncomment-428335)
* How to contribute / where to look first?
* [How to update](https://github.com/cryptoadvance/specter-desktop/discussions/909) \(scared to lose files / funds\)
* [Setup guides](https://github.com/cryptoadvance/specter-desktop/discussions/857) \(Full Node differences, local, remote, [remote over tor](https://github.com/cryptoadvance/specter-desktop/issues/604#issuecomment-728144342)\)

## Future Features

* [transaction / utxo labeling](https://github.com/cryptoadvance/specter-desktop/issues/826)
* [adding accounts](https://github.com/cryptoadvance/specter-desktop/issues/881), [multiple accounts on trezor](https://github.com/cryptoadvance/specter-desktop/discussions/1099) 
* hide balances / addresses, incognito mode for faster visual debugging when sharing screenshots
* [switch nodes or from mainnet to testnet](https://github.com/cryptoadvance/specter-desktop/issues/28)
* dashboard: node stats + wallet overview / summary 

## Minor Changes

[link formatting](https://github.com/cryptoadvance/specter-desktop/discussions/1099)

## Setups

* Local Bitcoin Core \(pruned / fullnode\) + Local Specter
* Remote Bitcoin Core \(pruned / fullnode\) + Local Specter
* Remote Bitcoin Core \(pruned / fullnode\) + Remode Specter

differences between local and public network? Tor / fullnode setup

## Notes

how to build confidence / trust in the setup? &gt; verify that it actually works, restore from backup in onboarding, guaranteed backup?

