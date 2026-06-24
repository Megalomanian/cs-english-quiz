# 第4章 计算机网络 — Computer Networks

---

## 📝 核心词汇

### 网络基础

| 单词 | 音标 | 释义 | 例句 | 备注 |
|:---|:---|:---|:---|:---|
| **computer network** | /kəmˈpjuːtə ˈnetwɜːk/ | 计算机网络 | A computer network includes two or more interconnected computer systems. | 核心特征：互联+协议+资源共享 |
| **topology** | /təˈpɒlədʒi/ | 拓扑 | The way devices are connected in a network is called topology. | 如总线型、星型、环型、网状 |
| **node** | /nəʊd/ | 节点 | In a bus topology, each computer is treated as a node on the bus. | 网络中的每个连接设备 |
| **protocol** | /ˈprəʊtəkɒl/ | 协议 | Networks use communication protocols to exchange data. | 网络通信的规则和标准 |
| **suite** | /swiːt/ | 套件，套组 | TCP/IP is a protocol suite used in many large networks. | TCP/IP 协议族 |
| **architecture** | /ˈɑːkɪtektʃə(r)/ | 架构 | Network architecture refers to the design of a computer network. | 包括物理组件和功能组织 |
| **backbone** | /ˈbækbəʊn/ | 骨干网 | The backbone provides the main data routes between networks. | 网络的主干 |

### 网络硬件与传输介质

| 单词 | 音标 | 释义 | 例句 | 备注 |
|:---|:---|:---|:---|:---|
| **modem** | /ˈməʊdem/ | 调制解调器 | A modem converts digital signals to analog and vice versa. | "猫"，拨号时代的经典设备 |
| **network interface card** | /ˈnetwɜːk ˈɪntəfeɪs kɑːd/ | 网卡 | Each computer needs a NIC to connect to the network. | 简称 NIC |
| **fiber optic cable** | /ˈfaɪbə ˈɒptɪk ˈkeɪbl/ | 光纤 | Fiber optic cables transmit data as light signals. | 高速、长距离、抗干扰 |
| **Ethernet** | /ˈiːθənet/ | 以太网 | Ethernet cable is the most common wired network connection. | 最常见的局域网技术 |
| **repeater** | /rɪˈpiːtə(r)/ | 中继器 | A repeater amplifies signals to counteract attenuation. | 放大信号，抵消衰减 |
| **concentrator** | /ˈkɒnsntreɪtə(r)/ | 集线器 | A concentrator connects multiple workstations at a central point. | 也称 hub（集线器） |
| **switch** | /swɪtʃ/ | 交换机 | A switch forwards each frame only to the correct destination based on MAC addresses. | 比集线器更智能，减少不必要流量 |

### 网络通信技术

| 单词 | 音标 | 释义 | 例句 | 备注 |
|:---|:---|:---|:---|:---|
| **collision** | /kəˈlɪʒn/ | 冲突 | A media access method handles collisions on the wire. | 如 CSMA/CD 协议 |
| **attenuation** | /əˌtenjuˈeɪʃn/ | 衰减 | Signals weaken over distance due to attenuation. | 需要中继器补偿 |
| **media access** | /ˈmiːdiə ˈækses/ | 介质访问 | Media access control determines how devices share the medium. | MAC 协议 |
| **bandwidth** | /ˈbændwɪdθ/ | 带宽 | Higher bandwidth allows faster data transmission. | 网络速度的关键指标 |
| **latency** | /ˈleɪtənsi/ | 延迟 | Low latency is critical for real-time applications. | 数据从源到目标的时间 |
| **MAC address** | /mæk əˈdres/ | MAC 地址 | A unique hardware identifier for each network interface. | Media Access Control address |

### 网络安全

| 单词 | 音标 | 释义 | 例句 | 备注 |
|:---|:---|:---|:---|:---|
| **authorization** | /ˌɔːθəraɪˈzeɪʃn/ | 授权 | Network security involves authorization of access to data. | 控制谁可以访问什么 |
| **authentication** | /ɔːˌθentɪˈkeɪʃn/ | 认证 | Users must authenticate using passwords or digital certificates. | 验证用户身份 |
| **encryption** | /ɪnˈkrɪpʃn/ | 加密 | Encryption protects data by converting it into unreadable code. | 数据安全的基石 |
| **malware** | /ˈmælweə(r)/ | 恶意软件 | Malware and spyware represent significant security threats. | 病毒、蠕虫、木马等 |
| **spyware** | /ˈspaɪweə(r)/ | 间谍软件 | Spyware covertly captures personal data without authorization. | 暗中窃取用户信息 |
| **firewall** | /ˈfaɪəwɔːl/ | 防火墙 | A firewall monitors and controls network traffic. | 网络安全第一道防线 |
| **digital certificate** | /ˈdɪdʒɪtl səˈtɪfɪkət/ | 数字证书 | Digital certificates verify the identity of users and servers. | 身份认证的电子凭证 |

### 网络模型与协议

| 单词 | 音标 | 释义 | 例句 | 备注 |
|:---|:---|:---|:---|:---|
| **peer-to-peer** | /pɪə tə pɪə/ | 点对点 | In P2P, all computers have equal status and share data directly. | 无需中心服务器 |
| **client-server** | /ˌklaɪənt ˈsɜːvə/ | 客户端-服务器 | The client-server model uses a central server to manage resources. | 最常见的网络架构 |
| **DNS** | /ˌdiːenˈes/ | 域名系统 | DNS translates domain names into IP addresses. | Domain Name System |
| **TCP** | /ˌtiːsiːˈpiː/ | 传输控制协议 | TCP ensures reliable, ordered delivery of data. | Transmission Control Protocol |
| **UDP** | /ˌjuːdiːˈpiː/ | 用户数据报协议 | UDP sends data without establishing a connection first. | 低延迟但可能丢包 |
| **IP** | /ˌaɪˈpiː/ | 互联网协议 | IP handles addressing and routing of packets. | Internet Protocol |
| **HTTPS** | /ˌeɪtʃtiːtiːpiːˈes/ | 安全超文本传输协议 | HTTPS encrypts data between browser and server. | HTTP + SSL/TLS |

---

## ✍️ 长句分析

### Sentence 1
> A computer network includes two or more interconnected computer systems that use communication protocols to share resources and exchange information.

**计算机网络包括两个或更多互联的计算机系统，它们使用通信协议来共享资源和交换信息。**

- **定语从句：** that use communication protocols... 修饰 computer systems
- **不定式：** to share resources and exchange information，表示目的
- **重点词汇：** interconnected（互联的）、communication protocols（通信协议）、share（共享）、exchange（交换）

### Sentence 2
> The way devices are connected in a network is called topology, with common types including bus, star, ring, and mesh, each offering different trade-offs between cost, reliability, and performance.

**网络设备的连接方式称为拓扑，常见类型包括总线型、星型、环型和网状，每种在成本、可靠性和性能之间提供不同的权衡。**

- **主语从句：** The way devices are connected...
- **with 复合结构：** common types including bus, star, ring, and mesh
- **重点词汇：** topology（拓扑）、trade-off（权衡）

### Sentence 3
> TCP/IP is a protocol suite that organizes communication into layers: IP handles addressing and routing of packets, while TCP ensures reliable delivery by detecting lost packets and requesting retransmission.

**TCP/IP 是一个将通信组织为多个层次的协议套件：IP 处理数据包的寻址和路由，TCP 通过检测丢失的数据包并请求重传来确保可靠交付。**

- **对比连词：** while，对比 IP 和 TCP 的不同职责
- **重点词汇：** suite（套件）、layer（层）、packet（数据包）、retransmission（重传）

### Sentence 4
> In the peer-to-peer model, all nodes have equal status and share data directly with one another, eliminating the need for a central server and making the system more resilient to single points of failure.

**在点对点模型中，所有节点地位平等，彼此直接共享数据，消除了对中心服务器的需求，并使系统对单点故障更具弹性。**

- **现在分词1：** eliminating the need for a central server
- **现在分词2：** making the system more resilient
- **重点词汇：** peer-to-peer（点对点）、resilient（有弹性的）、single point of failure（单点故障）

### Sentence 5
> Malware and spyware represent significant security threats, as malicious programs may encrypt user files for ransom or covertly capture personal data without authorization.

**恶意软件和间谍软件构成重大安全威胁，因为恶意程序可能加密用户文件以勒索赎金，或在未经授权的情况下秘密窃取个人数据。**

- **原因状语从句：** as malicious programs may encrypt... or covertly capture...
- **重点词汇：** malware（恶意软件）、spyware（间谍软件）、encrypt（加密）、ransom（赎金）、covertly（秘密地）

---

## 📄 核心概念

### 网络拓扑对比

| 拓扑 | 优点 | 缺点 |
|:---|:---|:---|
| 总线型 (Bus) | 简单、成本低 | 单点故障影响全网 |
| 星型 (Star) | 易管理、故障隔离 | 中心节点故障全瘫 |
| 环型 (Ring) | 等时传输、无冲突 | 单点断开全网瘫痪 |
| 网状 (Mesh) | 高可靠性、多路径 | 成本高、布线复杂 |

### P2P vs Client-Server

| 对比维度 | P2P | Client-Server |
|:---|:---|:---|
| 节点地位 | 平等 | 服务器为主，客户端为从 |
| 数据存储 | 分布式 | 集中在服务器 |
| 可扩展性 | 好（节点越多资源越多） | 受服务器性能限制 |
| 安全性 | 难管理 | 集中管理更安全 |

---

## 🗣️ 口语练习

**练习形式：** 网络方案设计讨论

**场景：** 为一家中小型企业设计办公网络方案。

**示例对话：**
- Q: "What network topology would you recommend for our office?"
- A: "I'd recommend a star topology because it's easy to manage and a single device failure won't bring down the entire network."
- Q: "How do we protect sensitive data?"
- A: "We need a firewall to filter traffic, encryption for data at rest and in transit, and proper user authentication."
- Q: "What protocols should we use?"
- A: "TCP/IP is the standard — it's reliable, widely supported, and powers the entire Internet."

---
*信息工程学院 丁彤 | tongding@nxu.edu.cn*
