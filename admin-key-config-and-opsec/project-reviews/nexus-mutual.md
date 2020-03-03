# Nexus Mutual 🆕

[Nexus Mutual](https://nexusmutual.io)'s smart contract pools are protected by an admin key controlled by the Mutual's 5 known Advisory Board members. The admin key is capable of making changes to critical parts of the smart contract ecosystem which could affect user deposits. Smart contract upgrades can occur with the approval of any 3+ board members. 

### Is the security of user funds dependent on opsec of admin key?

Yes ⚠️

### Current Admin Key Config

All smart contract changes are voted on in a GovBlocks DAO.   
3-of-5 consensus is required to implement changes.   
There is a 7-day mandatory voting period.

Governance DAO activity can be viewed at [https://app.nexusmutual.io/governance](https://app.nexusmutual.io/governance).

### Claimed Admin Key OpSec

It is claimed that each of the following Advisory Board members holds 1 hardware wallet signing key: ⚠️

* Hugh Karp
* Nitika Arora
* Rei Melbardis
* Nick Munoz-McDonald
* Graeme Thurgood

### Verified Admin Key OpSec

The past, present & future security of each signing key is unverifiable. ⚠️

### Admin Key Address

[https://etherscan.io/address/0x08c3a887865684f30351a0ba6d683aa9b539829a](https://etherscan.io/address/0x08c3a887865684f30351a0ba6d683aa9b539829a) 

### Response from Developer

> Nexus’ Funds are held in two contracts: 
>
> Pool1   
> [https://etherscan.io/address/0xfd61352232157815cf7b71045557192bf0ce1884](https://etherscan.io/address/0xfd61352232157815cf7b71045557192bf0ce1884) 
>
> Pool2   
> [https://etherscan.io/address/0x7cbe5682be6b648cc1100c76d4f6c96997f753d6](https://etherscan.io/address/0x7cbe5682be6b648cc1100c76d4f6c96997f753d6) 
>
> Staking is done in NXM, so this is managed by the token contracts and isn’t “funds” per se.
>
> Funds includes all member contributions in the mutual, which includes funds paid for coverage as well as direct purchases of NXM for ETH.
>
> All Nexus contracts are managed via our governance system which technically has 3 roles: 
>
> • Regular Member   
> • Advisory Board Member   
> • Owner Member 
>
> As per our note on the vulnerability disclosure, the Owner role now has the same rights as the Advisory Board Members. It previously could update centralised components such as KYC, quote engine and some other items but didn’t intentionally have access to funds \(the bug disclosure meant it effectively did\). 
>
> The powers of the Advisory Board roles are detailed in the disclosure doc \(repeated here\):   
> • Any Advisory Board member can categorise \(whitelist\) a proposal.   
> • At least three Advisory Board members are required to set the default outcome for proposals.   
> • At least three Advisory Board members are required to change category settings for proposals.   
> • At least three Advisory Board members are required to initiate the Emergency Pause.   
> • At least three Advisory Board members are required to change any centralised component \(such as quote engine, KYC, capital model\) or external feed addresses. 
>
> Until the bug fixes are in place 3+ AB members effectively have custody over the pool. After the bug fixes then custody passes to Members, but noting that AB members will still have reasonable powers that could cause significant damage if used maliciously \(eg centralised components\). So it could be argued that 3+ AB members are effectively trusted, even if it isn’t really custody of funds.
>
> Each AB member is a known individual \(and an official Director of Nexus Mutual LTD\) with their own hardware wallet. AB members do not work in the same office and while they do meet face-to-face on occasion they are spread out in different locations. There are also legal obligations on each Director to act in the best interest of the mutual and its members. Any smart contract upgrade or parameter change needs to pass through member governance which takes 1 week. After the bug fixes are in place, their will also be a speed bump of 24 hours after the voting period ends before the contracts are actually upgraded.

### More Info & Documentation

[Feb 2020 Vulnerability Disclosure](https://medium.com/nexus-mutual/responsible-vulnerability-disclosure-ece3fe3bcefa)

