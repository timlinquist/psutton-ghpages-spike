# Network Layout

### US
| Environment | DevOps VPC   | Data VPC      | OpsCenter VPC | Stable2 VPC   |
|-------------|--------------|---------------|---------------|---------------|
| KBUILD      | 10.18.0.0/16 | 10.29.0.0/16  | 10.0.0.0/16   | 10.97.0.0/16  |
| CPDEV       | Peered below | 10.150.0.0/16 | 10.0.0.0/16   | 10.98.0.0/16  |
| KDEV        | 10.7.0.0/16  | 10.17.0.0/16  | 10.0.0.0/16   | 10.96.0.0/16  |
| KQA         | 10.6.0.0/16  | 10.16.0.0/16  | 10.0.0.0/16   | 10.95.0.0/16  |
| KSTG        | 10.5.0.0/16  | 10.15.0.0/16  | 10.0.0.0/16   | 10.94.0.0/16  |
| KPROD       | 10.0.0.0/16  | 10.10.0.0/16  | 10.0.0.0/16   | 10.93.0.0/16  |

### EU
| Environment | DevOps VPC   | Data VPC      | OpsCenter VPC | Stable2 VPC   |
|-------------|--------------|---------------|---------------|---------------|
| KPROD-EU    | 10.202.0.0/18| 10.204.0.0/16 | 10.0.0.0/16   | 10.92.0.0/16  |

### Gov
| Environment | DevOps VPC   | Data VPC      | OpsCenter VPC | Stable2 VPC   |
|-------------|--------------|---------------|---------------|---------------|
| KGSTG       | 10.192.0.0/16| 10.196.0.0/16 | 10.0.0.0/16   | 10.91.0.0/16  |
| KGPROD      | 10.193.0.0/16| 10.194.0.0/16 | 10.0.0.0/16   | 10.90.0.0/16  |