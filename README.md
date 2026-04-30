# OpticsRx
光学像差溯源自愈多智能体系统 - 多Agent协同优化光学设计
[English](README_en.md) | 中文

## 项目简介

OpticsRx 是一个创新性的光学像差溯源自愈多智能体系统，通过长链推理与多Agent协作，
解决传统光学设计依赖专家经验的痛点问题。

## 核心特性

- 🎯 **多Agent协同**: Monitor、Strategist、Executor、Critic 四大Agent协同工作
- 📊 **15项像差监控**: 从低级球差到高级球色差的完整覆盖
- 🔍 **思维链推理**: 透明可追溯的推理过程
- 📈 **敏感度矩阵**: 量化分析各参数对像差的影响
- ✅ **闭环验证**: 基于物理模型的效果验证
- 🎉 **衍射极限检测**: 自动判断是否达到理论极限

## 性能指标

- 人工设计迭代次数: ~300次
- Agent自动化迭代次数: ~50次
- 迭代次数减少: **83%**
- Token消耗: ~200万

## 快速开始

### 安装

```bash
git clone https://github.com/yourusername/OpticsRx.git
cd OpticsRx
pip install numpy  # 仅完整版需要
