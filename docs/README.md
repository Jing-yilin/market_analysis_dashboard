# 使用文档

## 系统要求

- Python 3.8+
- pip 包管理器
- Git

## 安装步骤

1. 克隆仓库：
```bash
git clone https://github.com/Jing-yilin/market_analysis_dashboard.git
```

2. 安装依赖：
```bash
pip install -r requirements.txt
```

## 使用方法

### 基础分析
运行 `market_analysis.py` 获取基础市场分析：
```bash
python market_analysis.py
```

### 高级分析
运行 `enhanced_analysis.py` 获取包含技术指标的详细分析：
```bash
python enhanced_analysis.py
```

### 查看报告
- 基础报告：`market_report.md`
- 详细报告：`enhanced_report.md`

## 输出文件

- `market_analysis_1.png`: 主要市场指标可视化
- `market_analysis_2.png`: 技术分析可视化
- `market_stats.csv`: 统计数据