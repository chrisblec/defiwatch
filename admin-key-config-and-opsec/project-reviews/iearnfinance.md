# iearn.finance

[iearn.finance](https://iearn.finance) yDAI and yUSDC yield token contracts are not upgradeable and **do not** have admin keys.

The yUSDT yield token contract does have a powerful admin key which is planned to be burned after Compound adds its USDT market. This key has the power to add new USDT markets for rebalancing.

iearn's utility contracts have admin keys which can be used to artificially adjust the APY for each market, shifting users' funds between markets at the will of the admin. However, these movements are limited to the markets already coded into the yield token contracts.

yDAI and yUSDC funds can only be shifted between the legitimate markets written into their smart contracts, while yUSDT could potentially be shifted to a malicious contract added with its admin key.

Please note that funds deposited on iearn still inherit the risks of the downstream systems that it integrates with - like Compound, dYdX and Aave - which **do** still entail admin key risk.

### Is the security of user funds dependent on opsec of admin key?

yDAI: No ✅  
yUSDC: No ✅  
yUSDT: Yes ⚠️

### Current Admin Key Config

yDAI: N/A ✅  
yUSDC: N/A ✅  
yUSDT: No multisig, no timelock ⚠️

### Claimed Admin Key OpSec

yDAI: N/A ✅  
yUSDC: N/A ✅  
yUSDT: None ⚠️

### Verified Admin Key OpSec

yDAI: N/A ✅  
yUSDC: N/A ✅  
yUSDT: Unverifiable ⚠️

### Admin Key Address

yDAI: N/A ✅  
yUSDC: N/A ✅  
yUSDT: [https://etherscan.io/address/0x2d407ddb06311396fe14d4b49da5f0471447d45c](https://etherscan.io/address/0x2d407ddb06311396fe14d4b49da5f0471447d45c)

### More Info & Documentation

[iearn.finance Admin Policy Docs](https://docs.iearn.finance/adminpolicy)

### Credit

Thank you to **Andre Cronje of iearn.finance** for submitting a pull request for iearn and for his support in documenting this information.

