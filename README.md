Trader Behavior vs Market Sentiment Analysis

Objective

This project set out to answer a straightforward but important question:
Do traders behave differently when markets are driven by fear compared to when they are driven by optimism?

By combining market sentiment indicators with real trade-level data, the aim was to see how shifts in collective emotion translate into actual trading decisions, activity levels, and outcomes.

---

Approach

To explore this, I followed a structured analysis process:

- Examined both datasets to understand their structure, fields, and time alignment.
- Matched daily sentiment data with executed trades so each trade could be evaluated within the context of that day’s market mood.
- Built behavioral metrics such as:
  - Trade frequency (participation levels)
  - Profitability distribution
  - Win rate
  - Average trade size as a proxy for risk-taking
- Compared these behaviors across different sentiment regimes — Fear, Neutral, Greed, and Extreme conditions — to identify patterns.

---

Key Insights

- Trading activity increases noticeably during Fear phases, suggesting traders become more reactive in uncertain markets.
- Periods of Greed do not consistently translate into stronger profitability.
- Emotionally charged markets lead to greater variability in outcomes, not better performance.
- Overall, sentiment appears to influence how actively traders participate, rather than how successfully they trade — making it more useful as a behavioral and risk indicator than as a predictive trading edge.

---

Tools Used

- Python for analysis
- Pandas for data manipulation and transformation
- Matplotlib & Seaborn for visualization and exploratory insights

---

Conclusion

The analysis highlights that market sentiment has a clear impact on trader behavior — particularly in participation intensity and risk exposure.
However, it does not reliably improve trading success.

This suggests that sentiment is better incorporated into risk awareness and behavioral monitoring frameworks rather than treated as a standalone signal for decision-making.

---

Why This Matters

Understanding how traders react under emotional market conditions can help firms:

- Detect periods of reactive or crowd-driven activity
- Adjust risk controls during sentiment extremes
- Add behavioral context to existing trading strategies

In short, sentiment shapes behavior more than performance — and recognizing that distinction is key to managing risk effectively.
