# eos_registration
EOS Registration Results

## snapshot

Note that the **unclaimed** part of the EOS ERC-20 tokens is not included in our analysis.
Specifically, if an user pay to the [EOSCrowdsale contract](https://etherscan.io/address/0xd0a6e6c54dbc68db5db3a091b171a77407ff7ccf) on day X,
he/she can **claim** his/her share on day X+1.
Therefore, the corresponding ERC-20 tokens would be transferred to his/her balance at the [EOSTokenContract](https://etherscan.io/address/0x86fa049857e0209aa7d9e616f7eb3b3b78ecfdb0).
If he/she does not **claim**, eventually, his/her share would be included in the snapshot but **excluded in our snapshot data**.
