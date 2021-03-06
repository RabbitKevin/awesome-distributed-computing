﻿# Meeting with Ye-Ji (纪业)

## 2018-10-16 (周二)

两部分工作安排

### Redis: Replicated List 在 Redis 系统中的设计与实现

***项目特色: 基于 Redis、面向 Redis***

- OT 方法
	- [ ] 包括 OT 函数和控制函数 (多向张宇奇和江雪请教)
- CRDT 方法
	- [ ] 先完成 Attiya's RGA 算法的伪代码和TLA验证

### TLA+: State-space Graph 探索
- [ ] 两个工具的探索
- [ ] ***目标***: 交互式的 state-space graph

可能需要学习 Graphviz/Dot 和其它交互式网页设计工具

## 2018-10-29 (周一)
讨论工作进展:
- Redis
	- 初步了解C/S架构
- TLA toolbox (statespace visualizer)
	- 初步了解两个工具

确定近期工作（到本学期末）
- [ ] Redis List 实现
- [ ] TLA toolbox (statespace visualizer)
- [ ] CRDT
	- Attiya's RGA 算法的伪代码和 TLA+ 验证

## 2018-11-06 (周二; 下午)

1. Attiya's RGA 算法的 TLA+ 描述与验证工作:
	- 主要讨论了如何表示Tree结构
		- $G = (V, E)$ 使用node和edge集合表示
		- [ ] 挑战在于: 如何用 TLA+ 描述 tree 上的前序遍历算法
2. 两个 Dot Visualizer 工具
	-	现状: 在简单例子上仍然出错
	-	[ ] 建议: 到 TLA+ Googlegroup 上寻求帮助
