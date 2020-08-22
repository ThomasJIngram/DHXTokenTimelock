# DHXTokenTimelock


# 创始团队合约地址分配规则
两年后每月释放5%，20个月释放完。
```sh
  amount         1,000,000（锁仓数量)
  beneficiary    "0xB359eDB95cef97e5862E0899aE52be8e96E36cee"（锁仓地址）   
  start,          now+10s
  cliffDuration,  63072000s (2年）
  duration,       51840000s (20个月，每个月按照30天计算）
  revocable      false（不可以撤销）
```


# 投资机构团队合约地址分配规则
两年后每月释放5%，20个月释放完
```sh
  amount         600,000（锁仓数量)
  beneficiary    "0xDD6E4E63d71be7c238Cd408F2BFa4Bf6EF3b1d4D"（锁仓地址）   
  start,          now+10s
  cliffDuration,  63072000s (2年）
  duration,       51840000s (20个月，每个月按照30天计算）
  revocable      false（不可以撤销）
```

# 技术开发者团队合约地址分配规则
半年后每月释放10%，10个月释放完
```sh
  amount         500,000（锁仓数量)
  beneficiary    "0x9D58fDf0849Ad62226eD7D468606e39Dae1f3Bb0"（锁仓地址）   
  start,          now+10s
  cliffDuration,  15811200s (半年，半年按照183天）
  duration,       25920000s (10个月，每个月按照30天计算）
  revocable      false（不可以撤销）
```

# 剩余分配规则
立即释放
```sh
  amount         2,900,000（锁仓数量)
  beneficiary    "0x80c0B47D196F57d8A60B94b835007AECc0BE8Ece"（锁仓地址）   
  start,          now+10s
  cliffDuration,  0s 
  duration,       0s 
  revocable      false（不可以撤销）
```
