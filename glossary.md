# 量子通信中英术语表（初稿，待校）

> 翻译原则：优先采用国内已发布标准（GB/T、YD/T）的用语；无官方用语的标注"待定"并附候选译法。
> 欢迎通过 Issue/PR 修正。

| 英文 | 中文 | 说明 |
|---|---|---|
| QKD (quantum key distribution) | 量子密钥分发 | 利用量子力学特性在两个通信方之间分发对称密钥的技术 |
| QKDN (quantum key distribution network) | 量子密钥分发网络 | 支持 QKD 的网络，定义见 ITU-T Y.3800 |
| QKD module | 量子密钥分发模块 | 实现 QKD 协议的功能单元，含发送端与接收端 |
| QKD-Tx | 量子密钥分发发射机 | QKD 模块的发送部分 |
| QKD-Rx | 量子密钥分发接收机 | QKD 模块的接收部分 |
| quantum channel | 量子信道 | 用于传输量子信号的通信信道 |
| classical channel | 经典信道 | 通信双方交换经典数据的信道，数据可无损读取与复制 |
| QKD link | 量子密钥分发链路 | 两个 QKD 模块之间的通信链路（量子信道 + 经典信道） |
| QKDN node | 量子密钥分发网络节点 | QKDN 中的节点设备 |
| KM (key manager) | 密钥管理器 | 负责密钥生成、存储、供给等生命周期管理的功能实体 |
| key life cycle | 密钥生命周期 | 密钥从生成、存储、使用到删除/销毁的全过程 |
| key supply | 密钥供给 / 密钥充注 | 向加密应用提供密钥的过程（译法待定） |
| secure key | 安全密钥 | 经安全性确认、可用于加密应用的密钥 |
| QBER (quantum bit error rate) | 量子比特误码率 | 衡量量子信道质量与窃听风险的关键指标 |
| trusted relay / trusted node | 可信中继 / 可信节点 | 以逐段可信假设实现密钥中继的节点 |
| application link | 应用链路 | 用户网络中用于提供加密应用的通信链路 |
| QoS (quality of service) | 服务质量 | 服务性能的综合效果，决定用户对服务的满意度 |
| QKDN controller | QKDN 控制器 | 控制面功能实体，定义见 Y.3804 |
| QKDN manager | QKDN 管理器 | 管理面功能实体，定义见 Y.3804 |
| PQC (post-quantum cryptography) | 后量子密码 | 抗量子计算攻击的经典密码算法体系 |
| QRNG (quantum random number generator) | 量子随机数发生器 | 利用量子物理过程产生真随机数的设备 |

## 待补充

- 密钥中继相关：key relay、relay chain 等术语（待从 Y.3801/Y.3802 提取）
- 控制面/管理面信息模型相关术语（待从 Y.3804 提取）
- 国内标准用语对照（GB/T、YD/T 中的对应译法）
