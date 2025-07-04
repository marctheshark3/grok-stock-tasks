# grok-stock-tasks

Your stock market analysis alert system is designed to deliver actionable insights by monitoring market movements and integrating real-time data. Below are the prompts for each of your scheduled tasks, formatted in Markdown, incorporating the DataFrame-style view and the $1,000 scenario split into High Risk and Low Risk tables with Current Price, Number of Shares, Price Target, Estimated Profit, and Profit Percentage. These prompts are configurable—add or remove stocks by saying, "add these stocks to our analysis: <stock1>, <stock2>, ...<stockN>."

---

## ETF Mid-Week Analysis Prompt
Run post-market on Wednesday. Provide a concise ETF-focused analysis in a DataFrame-style view with columns: Ticker, Closing Price, Week-to-Date % Change, Event, RSI (14-day), Volume Change, Analyst Target. Include:
- **Mid-Week Market Snapshot**: Market trend (2-3 sentences), Key events remaining.
- **2/10 Spread**: Value and context (high/low volatility impact).
- **Investment Adjustments**: Short-term (1-3 months) and Long-term (6+ months) ETF strategies, Seasonality trend.
- **$1,000 Scenario**: High Risk and Low Risk tables with Allocation ($), Current Price ($), Number of Shares, Price Target ($), Estimated Profit ($), Profit %, Weight (%), Risk Level.
Use finance API for prices, web search for events, X search for sentiment. Keep output concise, citing reliable sources.

## Mid-Week Stock Analysis Prompt
Run post-market on Wednesday. Provide a concise stock analysis in a DataFrame-style view with columns: Ticker, Closing Price, Week-to-Date % Change, Event, RSI (14-day), Volume Change, Analyst Target. Include:
- **Mid-Week Market Snapshot**: Market trend (2-3 sentences), Key events remaining.
- **2/10 Spread**: Value and context (high/low volatility impact).
- **Top Movers**: Top gainer, Top loser, Notable mover (outside list).
- **Specific Stocks**: NVDA, AMD, FBTC, MSTR, COIN, TSLA, PLTR, INTC, MSFT, SOFI, TEM, ENPH, RIVN, SPOT, META.
- **Investment Adjustments**: Short-term (1-3 months) and Long-term (6+ months) strategies, Seasonality trend.
- **$1,000 Scenario**: High Risk and Low Risk tables with Allocation ($), Current Price ($), Number of Shares, Price Target ($), Estimated Profit ($), Profit %, Weight (%), Risk Level.
Use finance API for prices, web search for events, X search for sentiment. Keep output concise, citing reliable sources. Add stocks with: NVDA, AMD, FBTC, MSTR, COIN, TSLA, PLTR, INTC, MSFT, SOFI, TEM, ENPH, RIVN, SPOT, BMNR and META.

## Weekly Portfolio Review and Rebalancing Prompt
Run on Friday post-market or Saturday. Provide a concise portfolio review in a DataFrame-style view with columns: Ticker, Closing Price, Weekly % Change, Risk. Include:
- **Portfolio Performance**: Weekly gain/loss (overall %), Top performer, Bottom performer.
- **Specific Stocks**: NVDA, AMD, FBTC, MSTR, COIN, TSLA, PLTR, INTC, MSFT, SOFI, TEM, ENPH, RIVN, SPOT, META.
- **Rebalancing Suggestions**: Reduce exposure, Increase exposure, New opportunity (outside list), Seasonality trend.
- **$1,000 Scenario**: High Risk and Low Risk tables with Allocation ($), Current Price ($), Number of Shares, Price Target ($), Estimated Profit ($), Profit %, Weight (%), Risk Level.
Use finance API for prices, web search for risk factors, X search for sentiment. Keep output concise, citing reliable sources. Add stocks with: NVDA, AMD, FBTC, MSTR, COIN, TSLA, PLTR, INTC, MSFT, SOFI, TEM, ENPH, RIVN, SPOT, and META.

## Weekly Sector and Macro Analysis Prompt
Run on Sunday evening or Monday pre-market. Provide a concise analysis in a DataFrame-style view with columns: Ticker, Sector Impact, News. Include:
- **Macroeconomic Overview**: Key indicators (2-3 sentences), Global events.
- **Sector Trends**: Tech, EV, Fintech/Crypto, Energy, Consumer, Funds.
- **Specific Stocks**: NVDA, AMD, FBTC, MSTR, COIN, TSLA, PLTR, INTC, MSFT, SOFI, TEM, ENPH, RIVN, SPOT, META.
- **Investment Opportunities**: Short-term (1-3 months) and Long-term (6+ months) strategies, Seasonality trend.
- **$1,000 Scenario**: High Risk and Low Risk tables with Allocation ($), Current Price ($), Number of Shares, Price Target ($), Estimated Profit ($), Profit %, Weight (%), Risk Level.
Use web search for macro and sector trends, X search for sentiment, finance API for stock data. Keep output concise, citing reliable sources. Add stocks with: NVDA, AMD, FBTC, MSTR, COIN, TSLA, PLTR, INTC, MSFT, SOFI, TEM, ENPH, RIVN, SPOT, BMNR and META.

## End of Week Stock Analysis Prompt
Run Friday post-market. Provide a concise stock analysis in a DataFrame-style view with columns: Ticker, Closing Price, Weekly % Change, Event. Include:
- **Weekly Performance**: Market summary (2-3 sentences), Top 3 gainers, Top 3 losers.
- **Specific Stocks**: NVDA, AMD, FBTC, MSTR, COIN, TSLA, PLTR, INTC, MSFT, SOFI, TEM, ENPH, RIVN, SPOT, META.
- **Investment Strategies**: Short-term (1-3 months) and Long-term (6+ months) strategies, Seasonality trend.
- **$1,000 Scenario**: High Risk and Low Risk tables with Allocation ($), Current Price ($), Number of Shares, Price Target ($), Estimated Profit ($), Profit %, Weight (%), Risk Level.
Use finance API for prices, web search for performance, X search for sentiment. Keep output concise, citing reliable sources. Add stocks with: NVDA, AMD, FBTC, MSTR, COIN, TSLA, PLTR, INTC, MSFT, SOFI, TEM, ENPH, RIVN, SPOT, BMNR and META.

## Weekly Pre-Market Stock Analysis Prompt
Run Monday pre-market. Provide a concise stock analysis in a DataFrame-style view with columns: Ticker, Pre-market Price, News, Analyst. Include:
- **Market Outlook**: Weekly economic trends (2-3 sentences), Key events this week.
- **Stock Predictions**: [Stock 1], [Stock 2], [Stock 3] (include one outside list).
- **Specific Stocks**: NVDA, AMD, FBTC, MSTR, COIN, TSLA, PLTR, INTC, MSFT, SOFI, TEM, ENPH, RIVN, SPOT, META.
- **Investment Strategies**: Short-term (1-3 months) and Long-term (6+ months) strategies, Seasonality trend.
- **$1,000 Scenario**: High Risk and Low Risk tables with Allocation ($), Current Price ($), Number of Shares, Price Target ($), Estimated Profit ($), Profit %, Weight (%), Risk Level.
Use finance API for prices, web search for news, X search for sentiment. Keep output concise, citing reliable sources. NVDA, AMD, FBTC, MSTR, COIN, TSLA, PLTR, INTC, MSFT, SOFI, TEM, ENPH, RIVN, SPOT, BMNR and META.

## Daily Pre-Market Stock Analysis Prompt
Run daily pre-market. Provide a concise stock analysis in a DataFrame-style view with columns: Ticker, Pre-market Price, News, Analyst. Include:
- **Market Sentiment**: Economic outlook (2-3 sentences), Key events today.
- **Stock Predictions**: [Stock 1], [Stock 2], [Stock 3] (include one outside list).
- **Specific Stocks**: NVDA, AMD, FBTC, MSTR, COIN, TSLA, PLTR, INTC, MSFT, SOFI, TEM, ENPH, RIVN, SPOT, META.
- **Investment Opportunities**: Short-term (1-3 months) and Long-term (6+ months) strategies, Seasonality trend.
- **$1,000 Scenario**: High Risk and Low Risk tables with Allocation ($), Current Price ($), Number of Shares, Price Target ($), Estimated Profit ($), Profit %, Weight (%), Risk Level.
Use finance API for prices, web search for news, X search for sentiment. Keep output concise, citing reliable sources. Add stocks with: NVDA, AMD, FBTC, MSTR, COIN, TSLA, PLTR, INTC, MSFT, SOFI, TEM, ENPH, RIVN, SPOT, BMNR and META.
---

These prompts ensure consistency across tasks, leveraging your preferred format and data points. Let me know if you’d like to test any specific prompt or adjust further!
