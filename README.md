##

All tasks were deployed on Sepolia network.  
PriceFeed Contract = 0xA4Ce53064DA9a1220F314f97bAE8a8D19B730FD6  
VRF Contract = 0x48Ff440B5a36f5dca8aF89b21ec527C26cb5C196  
Automation Contract = 0x9FE0B163E96C95a9e29A7850A17a786473ecDa90  

There are the test results for PriceFeed,VRF and Automation contracts below.  

Compiled 63 Solidity files successfully  

单元测试：Chainlink Data feed  
✔ 单元测试 0-0：LINK aggregator 地址配置正确 (7183ms)  
✔ 单元测试 0-1：BTC aggregator 地址配置正确  
✔ 单元测试 0-2：ETH aggregator 地址配置正确  
✔ 单元测试 0-3: Link aggregator 地址配置正确  
✔ 单元测试 0-4: BTC aggregator 返回正确结果  
✔ 单元测试 0-5: ETH aggregator 返回正确结果  
✔ 单元测试 0-6: LINK aggregator 返回正确结果  

单元测试：Chainlink VRF  
✔ 单元测试 1-0: VRF 请求成功发送 (139ms)  
✔ 单元测试 1-1: 成功接受到随机数 (69ms)  
✔ 单元测试 1-2: 成功得到 5 个不重复的随机数 (68ms)  

单元测试：Chainlink Automation  
✔ 单元测试 2-0： 状态未发生变化时，checkUpkeep 返回 false (50ms)  
✔ 单元测试 2-1：满足 checkUpkeep 状态时，成功执行 performUpkeep (74ms)  

