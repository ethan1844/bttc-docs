# 端口管理

以下是 Bttc和Delivery节点使用的默认端口列表：


## Bttc

| ﻿名字                   | 端口  | 标签                      | 描述                                                                                                    |
|------------------------|-------|---------------------------|----------------------------------------------------------------------------------------------------------------|
| 网络监听 | 30303 | 公开                   | 网络监听端口，Bttc节点使用该端口来连接其他Bttc节点，并同步区块。                                      |
| Websocket 服务              | 8546  | 公开或者私密   | Websocket端口。 |
| Pprof 服务           | 7071  | 私密     | Pprof服务,从Bttc节点收集分析数据。                                                                      |
| UDP 发现服务          | 30303 | 公开或者私密 | 用于节点发现服务。  |
| RPC 服务             | 8545  | 公开或者私密   | RPC API服务,可以向Bttc节点发送交易或者从Bttc节点获取数据。|                                                                   |




## Delivery

| ﻿名字                   | 端口  | 标签                      | 描述                                                                                                    |
|------------------------|-------|---------------------------|----------------------------------------------------------------------------------------------------------------|
| RPC 服务             | 26657  | 公开或者私密   | RPC API服务,可以向Delivery节点发送交易或者从Delivery节点获取数据。|                                                                   |
| Prometheus 服务             | 26660  | 公开或者私密   | Prometheus API服务。 |               |
| P2P 服务             | 26656  |  公开或者私密  | 网络监听端口，Delivery节点使用该端口来连接其他Delivery节点，并同步区块 |               |
| Pprof 服务           | 6060  | 私密     | Pprof服务,从Delivery节点收集分析数据。                                                                      |
