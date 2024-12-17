# Market Analysis Dashboard

A comprehensive market analysis tool that provides technical indicators and visualizations for financial market data.

## Features

- Multiple technical indicators (MACD, RSI, Moving Averages)
- Advanced data visualization
- Statistical analysis
- Automated report generation
- Real-time market data processing

## Project Structure

```
market_analysis_dashboard/
├── market_analysis.py       # Basic analysis script
├── enhanced_analysis.py     # Advanced analysis with technical indicators
├── requirements.txt         # Project dependencies
├── market_report.md        # Basic market report
└── enhanced_report.md      # Detailed analysis report with technical indicators
```

## Setup

1. Clone the repository:
```bash
git clone https://github.com/Jing-yilin/market_analysis_dashboard.git
cd market_analysis_dashboard
```

2. Create and activate virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Run basic analysis:
```bash
python market_analysis.py
```

2. Run enhanced analysis with technical indicators:
```bash
python enhanced_analysis.py
```

## Generated Files

- `market_analysis_1.png`: Main market indicators visualization
- `market_analysis_2.png`: Advanced technical analysis visualization
- `market_stats.csv`: Statistical data
- `market_report.md`: Basic market analysis report
- `enhanced_report.md`: Comprehensive market analysis report

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- scipy
- yfinance

## License

MIT License

## Contributing

Feel free to submit issues and enhancement requests!