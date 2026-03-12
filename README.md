<p align="center">
  <img src="docs/assets/tashan.svg" alt="他山 Logo" width="200" />
</p>

<p align="center">
  <strong>数字分身 1→100 迭代逼近系统</strong><br>
  <em>Digital Twin Iteration: Fidelity Growth (1→100)</em>
</p>

<p align="center">
  <a href="#项目简介">简介</a> •
  <a href="#核心内容">核心内容</a> •
  <a href="#生态位置">生态位置</a> •
  <a href="#贡献">贡献</a> •
  <a href="README.en.md">English</a>
</p>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![状态](https://img.shields.io/badge/状态-待开始-lightgrey)

> 🔲 **本仓库当前为骨架仓库，等待正式开发启动。依赖 ④ 的稳定 Profile Schema。**

---

## 项目简介

### 在大框架中的位置

数字分身路径的**第二阶段：1→100**——这不是数量扩展，而是**保真度持续提升**。

初始分身（④的产出）只是一个低保真的起点。本项目解决的核心问题是：**一个数字分身如何在长期交互和世界内演化中越来越接近真人？**

分身不只因为用户说了更多信息而变好，更因为它在数字世界中不断行动、被纠偏、积累历史、形成关系——这些行为证据成为分身精化的素材。

### 核心设计

**分身迭代机制**：
- 真人纠偏（用户对分身输出的反馈）
- 长期对话积累（跨会话的记忆沉淀）
- 行为日志（世界内协作痕迹）
- 多源证据融合（量表/对话/行为/反馈）

**保真度评测体系**（五维度）：

| 维度 | 说明 |
|------|------|
| 自陈一致性 | 分身对自我描述的稳定性 |
| 行为一致性 | 行动与声称风格的匹配度 |
| 风格一致性 | 词汇、语气、句法的保真度 |
| 关系一致性 | 与他人互动模式的稳定性 |
| 长期稳定性 | 跨时间的整体人格稳定性 |

**分身验证等级**：弱保真（低风险场景）↔ 高保真（强社会模拟 / 代理协作）

### 目标读者

- AI 研究者：研究数字孪生的保真度评测方法
- 产品开发者：构建个性化 AI 的长期迭代机制
- 认知科学研究者：研究数字化人格的慢变量与快变量

---

## 核心内容

> 📋 以下为规划内容，随开发进展持续填充。

- `迭代引擎/`：基于多源证据的分身状态更新机制
- `评测框架/`：五维保真度评测体系实现
- `验证等级/`：弱保真 / 高保真分层标准与判定规则
- `基准测试/`：与 BehaviorChain、TwinVoice 等现有基准的对比

---

## 生态位置

| 层级 | 项目 | 仓库 | 类型 | 状态 |
|------|------|------|------|:----:|
| 世界底座 | ① 公理体系 | [world-axiom-framework](https://github.com/TashanGKD/world-axiom-framework) | 开源 | 🔲 |
| 世界底座 | ② 体系结构 | [world-three-particle-impl](https://github.com/TashanGKD/world-three-particle-impl) | 开源 | 🔲 |
| 世界底座 | ③ 沙盘验证 | [world-sandbox-validation](https://github.com/TashanGKD/world-sandbox-validation) | 开源 | 🔲 |
| 数字分身 | ④ 0→1构建 | [digital-twin-bootstrap](https://github.com/TashanGKD/digital-twin-bootstrap) | 开源 | 🟡 |
| 数字分身 | **⑤ 1→100迭代** ← 本仓库 | [digital-twin-iteration](https://github.com/TashanGKD/digital-twin-iteration) | 开源 | 🔲 |
| 核心应用 | 数字世界应用 | TashanGKD/tashan-world（私有） | 私有 | 🔲 |
| 商业化 | 数字分身平台 | TashanGKD/tashan-twin-platform（私有） | 私有 | 🔲 |
| 公益 | 他山论坛 | [tashan-forum](https://github.com/TashanGKD/tashan-forum) | 开源公益 | 🔲 |

**直接依赖关系**：
- 本仓库依赖 ④ 输出的稳定 Profile Schema 作为输入
- 本仓库的分身数据格式变动会触发**场景L**（通知上层应用适配）
- ① 公理关于 Agent State 的定义变动会触发**场景K**（通知本仓库评估）

---

## 贡献

欢迎贡献！详见 [CONTRIBUTING.md](CONTRIBUTING.md)（待建）。

---

## 更新日志

见 [CHANGELOG.md](CHANGELOG.md)（待建）。

---

## 许可证

MIT License. See [LICENSE](LICENSE) for details.
