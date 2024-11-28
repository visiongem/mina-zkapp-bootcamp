1. 概述Mina所采用的证明系统(包括名称、特点)

### 名称
- **Pickles**：Mina 使用的零知识证明系统。

### 特点
1. **递归零知识证明**：
    - Pickles 是 Mina 网络中实现递归零知识证明的核心工具，允许证明者生成一种可嵌套的证明。
2. **高效性**：
    - 利用零知识证明压缩链上数据，只需存储网络的简洁证明（zk-SNARK），而非整个区块链。
3. **无需可信设置**：
    - 使用 Halo 技术，避免了 zk-SNARK 系统中的可信设置需求，增强了去中心化和安全性。
4. **支持通用性**：
    - 允许用户编写任意逻辑和智能合约（zkApps），提供更大的灵活性。

2. 概述递归零知识证明在 Mina 共识过程中的应用

### 核心应用
Mina 将整个区块链的状态压缩为一个小型 zk-SNARK 证明，称为 **“State Proof”（状态证明）**。

### 具体过程
1. **简洁证明**：
    - 每个新区块的状态被递归证明，生成一个新的小型 zk-SNARK。
2. **验证效率**：
    - 节点只需要验证最新的 zk-SNARK，而不是从创世块开始验证整个链。
3. **存储需求**：
    - 全节点只需几十 KB 的数据，极大地降低存储需求，用户可以轻松运行全节点。

### 优点
1. **极简区块链**：
    - Mina 被称为“世界上最轻的区块链”，其大小仅保持在约 22 KB。
2. **快速同步**：
    - 节点无需下载历史数据，可以快速参与网络。
3. **隐私保护**：
    - 零知识证明本质上保护了交易细节和用户隐私。


3. 下载安装 [Auro wallet](https://www.aurowallet.com/download/)，创建账户，并完成[领水](https://faucet.minaprotocol.com/)




请提交回答，钱包账户截图和领水 `tx hash`。

截图[wallet](./wallet.png)

# 交易哈希详情
5JurCee5T9CVSLjqo3KaY4NYkLnYfL8zhR59Hw88s2xhHE7dXqsf
