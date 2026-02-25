# 南科大AI刷题助手（SUSTech-AI-StudyHelper）
✨ 面向ACM/蓝桥杯/LeetCode刷题的智能助手，结合算法+AI，解决刷题没方向、卡题没思路、错题不复盘的问题

## 🎯 核心功能
- 📚 智能选题：按知识点/难度/错题率推荐题目（贪心算法）
- 🤖 AI思路讲解：ACM/蓝桥杯风格解题思路（无完整代码）
- 📝 错题本：自动归类+薄弱点分析（拓扑排序/前缀和）
- 📊 刷题统计：生成知识点掌握度报表

## 🛠 技术栈
- 核心语言：Java（工程交互） + C++（算法核心）
- 算法：贪心、DP、拓扑排序、前缀和
- AI：智谱GLM-4-mini（轻量级LLM）
- 工具：JNA（Java调用C++）、FastJSON、Maven

## 🚀 快速开始
### 环境要求
- JDK 8+ / GCC 9+
- Maven 3.6+
- 智谱AI API Key（免费申请：https://www.bigmodel.cn/）

### 运行步骤
1. 克隆仓库：
   ```bash
   git clone https://github.com/你的GitHub用户名/SUSTech-AI-StudyHelper.git
   cd SUSTech-AI-StudyHelper
