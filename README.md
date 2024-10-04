# MergersAcquisitions-Stock-Sentiment-Tech
An analysis of stock price movements and sentiment of news articles for five companies that underwent mergers or acquisitions. This project explores the impact of corporate mergers and acquisitions on stock performance and examines sentiment trends in related news coverage.

---
## Mergers and Acquisitions: Sentiment and Stock Price Analysis

This project analyzes the stock price movements and sentiment of news articles for five companies that went through mergers and acquisitions. The goal is to understand how corporate events impact stock performance and market sentiment. The companies analyzed are Palo Alto Networks (PANW), Dell Technologies (DELL), Cognizant Technology Solutions (CTSH), Accenture (ACN), and CyberArk (CYBR).

### Steps:
1. **Data Collection**:
   - Used web scraping to gather news articles from Yahoo Finance for each company.
   - Retrieved stock price data using the `yfinance` API, focusing on the periods surrounding the mergers or acquisitions.
   
2. **Sentiment Analysis**:
   - Applied the VADER Sentiment Intensity Analyzer from NLTK to perform sentiment analysis on the article titles.
   - Classified articles as positive, neutral, or negative based on sentiment scores.

3. **Stock Price Correlation**:
   - Analyzed stock price fluctuations before and after the news articles were published.
   - Visualized the relationship between sentiment scores and stock performance using charts, such as line, bar, and candlestick charts.

### Company Insights:
- **Palo Alto Networks (PANW)**:
  Despite positive sentiment around its AI partnerships, PANW stock experienced a decline after the announcements. This suggests that the market may have already priced in the news, or broader market conditions contributed to the drop.

- **Dell Technologies (DELL)**:
  Dell’s stock showed mixed reactions, with a drop following the CEO’s $1.2 billion stock sale, but it recovered due to positive news regarding AI expansion and eco-friendly partnerships.

- **Cognizant Technology Solutions (CTSH)**:
  Cognizant saw a positive stock price trend, driven by highly favorable sentiment surrounding its AI acquisitions and partnerships. Investors reacted positively to the company's strategic moves in AI.

- **Accenture (ACN)**:
  Accenture's stock increased steadily after news of its collaboration with Nvidia on AI solutions. The positive sentiment reflected investor optimism about the company’s role in AI-driven corporate solutions.

- **CyberArk (CYBR)**:
  Even with a major acquisition of Venafi, CyberArk’s stock dropped due to neutral sentiment and market caution. Investors may have been unsure about the short-term impact of the acquisition on profitability.

### Conclusion:
The analysis reveals that while positive sentiment often accompanies mergers and acquisitions, immediate stock reactions are influenced by various factors, including market conditions, investor expectations, and the perceived long-term benefits of these strategic moves.

