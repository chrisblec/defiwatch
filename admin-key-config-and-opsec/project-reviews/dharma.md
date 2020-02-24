# Dharma

[Dharma](https://dharma.io) users' smart wallets are all upgradeable via a 3-of-5 multisig admin contract with a 7-day timelock. Dharma is capable of making updates to the smart wallet code and is also capable of freezing accounts.

#### Is the security of user funds dependent on opsec of admin key?

Yes ⚠️

#### Current Admin Key Config

Timelock: 7 days  
Multisig: 3-of-5

#### Claimed Admin Key OpSec

None

#### Verified Admin Key OpSec

Unverifiable ⚠️

#### Admin Key Address

[https://etherscan.io/address/0x00000001008b2ff2004f00a7c8a0f48c675e5034](https://etherscan.io/address/0x00000001008b2ff2004f00a7c8a0f48c675e5034)

#### More Info & Documentation

[Tweets on security](https://twitter.com/Dharma_HQ/status/1195168777064738816?s=20)   
[Github ReadMe \(section: Upgradeability\)](https://github.com/dharma-eng/dharma-smart-wallet)

#### Statement from Dharma

> Hey there - author of the Dharma Smart Wallet and related contracts here. \(This is a fantastic initiative, by the way - transparency is an incredibly important aspect of decentralized finance!\)
>
> I’d like to share a few details on our admin key opsec:
>
> * As you’ve already pointed out, we utilize a 3/5 multisig in order to upgrade our contracts. The multisig is extremely similar to [Christian Lundkvist’s Simple Multisig](https://github.com/christianlundkvist/simple-multisig), which is audited by Consensys Diligence, and our particular implementation has been audited by Trail of Bits.
> * While, like other projects, I’d be hesitant to share _too_ many details about our key management, I will say that we utilize a pretty involved, multi-stage process, with the signing stage isolated to an independent, offline context, and with redundant verification performed at each stage \(both automatic and manual\). The private keying material has never been “hot” at any point. \(I’d be really interested in learning how this could be verifiable somehow!\)
> * The primary defense against malfeasance on our part when it comes to system upgrades, as you also highlight, is the 7-day timelock - I believe this is one of the more conservative durations in DeFI, but in our view it is important so that users have plenty of time to exit the system if there’s an upgrade they disagree with. We do our best to get the word out whenever we’re making changes, but I would _love_ to work with anybody interested in setting up third-party monitoring tools for our contracts, or for DeFi at large, to send out alerts and additional context whenever upgrades or other changes are queued up or executed.
>
> Happy to answer any other questions concerning the Dharma Smart Wallet and other contracts, and moreover I’m always open to suggestions on how to improve our system further!
>
> 0age

