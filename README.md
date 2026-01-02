# Quantitative Trading & Algorithm Development

Hi, I'm a high school student passionate about quantitative finance and algorithmic trading. I build automated trading systems, backtest strategies, and explore how code can be applied to financial markets.

## About Me

I'm interested in the intersection of programming and finance. I spend my time developing trading bots, analyzing market data, and learning about quantitative strategies. I'm looking to gain real-world experience in the finance industry through internships and mentorship opportunities.

**Location:** Beacon Falls, Connecticut  
**Expected Graduation:** June 2027

## Technical Skills

- **Programming:** Python (pandas, NumPy, scikit-learn, PyTorch), JavaScript, SQL
- **Machine Learning:** RandomForest, Gradient Boosting, Logistic Regression, PPO (Reinforcement Learning)
- **Quantitative Finance:** Futures trading, portfolio optimization, technical analysis, backtesting, risk management
- **Tools & Technologies:** Git, SQLite, yfinance, Google Colab, stable-baselines3, PyPortfolioOpt
- **Data Science:** Statistical modeling, feature engineering, time series analysis, K-Means clustering

## Projects

### Multi-Asset Reinforcement Learning Trading System
**December 2025**

Developed autonomous trading system using PPO (Proximal Policy Optimization) to trade 30-asset portfolio.
- Trained on 100,000 timesteps with transaction cost modeling (5bps per trade)
- Engineered 300+ technical features per asset including momentum indicators, volatility measures, RSI, MACD, Bollinger Bands, and ADX across multiple timeframes
- Implemented deep neural network policy (256-256-128 architecture) with risk-adjusted reward function to balance returns against volatility
- Performed rigorous out-of-sample validation: trained on 2020-2023 data, tested on unseen 2024-2025 data

**Technologies:** Python, PyTorch, stable-baselines3, gymnasium, reinforcement learning, deep learning

### E-mini S&P 500 Futures Automated Trading System
**December 2025**

Built automated ES futures trading bot using ICT (Inner Circle Trader) methodology with Fair Value Gap detection.
- Implemented dynamic position sizing based on ATR volatility, risking 1% of capital per trade with 2:1 reward-to-risk ratio
- Developed session-based trading logic (NY AM/PM, London, Asian killzones) with real-time entry/exit management
- Achieved 70% win rate over 10 trades with $10,000 profit through multi-timeframe FVG analysis
- Created comprehensive trade journaling system with SQLite database tracking entry/exit prices, P&L, session performance, and trade duration analytics

**Technologies:** Python, yfinance API, futures market microstructure, order flow analysis, real-time data processing

### Quantitative Momentum Portfolio with Mean-Variance Optimization
**November 2025**

Built systematic portfolio strategy using K-Means clustering and Markowitz mean-variance optimization across 100-stock universe.
- Implemented Garman-Klass volatility estimator, multi-period momentum signals (1, 2, 3, 6-month), and RSI-based regime classification
- Optimized monthly portfolio rebalancing using Efficient Frontier to maximize Sharpe ratio with diversification constraints
- Achieved 119% total return (23% annualized) vs 37% S&P 500 benchmark with 1.19 Sharpe ratio

**Technologies:** Python, PyPortfolioOpt, scikit-learn, K-Means clustering, modern portfolio theory

### Genetic Algorithm Gold Futures Trading System
**October 2025**

Developed ML-powered gold futures strategy achieving 110% backtested return over 60 days with 63% win rate.
- Implemented genetic algorithm optimizer (15 generations, population 20) to evolve optimal EMA parameters and ATR-based risk management
- Built ensemble ML model combining RandomForest, GradientBoosting, and LogisticRegression on hourly timeframe data
- Engineered 17 technical indicators including EMA crossovers, Stochastic oscillators, price action patterns, and volume analysis

**Technologies:** Python, scikit-learn, genetic algorithms, time series analysis

### Cryptocurrency Trading Bot Development
**Summer 2025**

Researched and developed automated trading bots for Solana blockchain token analysis.
- Integrated real-time WebSocket connections and API data feeds for market monitoring
- Explored machine learning for price prediction and pattern recognition on high-frequency crypto data
- Built database systems for historical analysis and performance tracking

**Technologies:** Python, WebSocket APIs, blockchain data analysis, SQLite

## What I'm Learning

I'm continuously expanding my knowledge in:
- Options pricing models and statistical arbitrage
- Reinforcement learning applications in trading
- Portfolio theory and risk management
- Smart money concepts and institutional order flow analysis

## Contact

**Email:** adrian.salgado2027@gmail.com  
**Phone:** (860) 933-9151

Feel free to reach out if you'd like to discuss quantitative finance, trading systems, or potential opportunities.

---

