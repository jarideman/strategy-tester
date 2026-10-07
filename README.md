from pathlib import Path

content = """# Trading Strategy Tester

## Strategy Rules
- [ ] Entry / exit rules
- [ ] Position sizing
- [ ] SL / TP / trailing stop
- [ ] Max positions / pyramiding

## Execution & Costs
- [ ] Spread
- [ ] Commission
- [ ] Swap
- [ ] Slippage
- [ ] Execution delay
- [ ] Broker / symbol specifications

## Trade Data
- [ ] Entry / exit time & price
- [ ] Direction & lot size
- [ ] SL / TP
- [ ] Gross & net P/L
- [ ] Fees
- [ ] MFE / MAE
- [ ] Exit reason

## Performance
- [ ] Net profit / return
- [ ] Profit factor
- [ ] Expectancy
- [ ] Win rate
- [ ] Avg win / loss
- [ ] Max drawdown & duration
- [ ] Losing / winning streak
- [ ] Sharpe / Sortino
- [ ] Equity & drawdown curves

## Robustness
- [ ] In-sample / out-of-sample
- [ ] Walk-forward testing
- [ ] Parameter sensitivity
- [ ] Higher spread / commission / slippage
- [ ] Different market conditions
- [ ] Different symbols / timeframes
- [ ] Monte Carlo testing
- [ ] Overfitting checks

## Reporting
- [ ] Save strategy + parameters
- [ ] Save test period & market data
- [ ] Save broker / execution settings
- [ ] Export trades & results
- [ ] Reproducible test results

## Final Validation
- [ ] Positive expectancy
- [ ] Acceptable drawdown
- [ ] Enough trades
- [ ] Stable parameters
- [ ] Profitable out-of-sample
- [ ] Profitable walk-forward
- [ ] Robust Monte Carlo results
- [ ] Survives realistic trading costs
- [ ] Forward / paper test completed
