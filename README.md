# DIY ETF Investing

<p align="center">
  <img src="Asset Structure.png" alt="Top-down Asset Allocation" style="width:100%">
</p>
<p align="center">
  <i>Top-down Asset Allocation</i>
</p>

To simplify ETF portfolio setup, management, and rebalancing for friends, I created the **Rebalancing Cockpit** Excel file, which is available here. I'm sharing it to inspire other DIY ETF savers and investors in designing their portfolios.

## Target Portfolio

### Level 1 Allocation

Users first need to set their target allocation by adjusting these parameters:

- **Age**: Your age implicitly dictates how much risk you can bear, especially if you're primarily saving for retirement. More time before retirement allows for riskier investments, as there's more time to recover from market downturns. In this portfolio model, the portfolio is split into a *high-risk* equity portion and a *low-risk* fixed income portion. The equity allocation is computed using the following heuristic:

$$
\text{Equity Allocation} = \frac{100 - \text{Age}}{100}
$$

In a more professional context, determining the appropriate equity allocation involves a multifactorial optimization problem that includes long-term liabilities, short-term liquidity needs, risk constraints, and personal utility functions. As mentioned above, this is a heuristic for DIY investors.

### Level 2 Allocation

The **high-risk equity portion** can be further diversified with two primary risk factors or sources of return, if desired:

- **Value Factor**: Stocks that are cheaply valued (*value stocks*), as indicated by metrics such as the price-earnings ratio, tend to outperform highly valued stocks (*growth stocks*).
- **Momentum Factor**: Stocks with recent high returns tend to continue outperforming for a short period, and vice versa.

The fixed income portion can also be diversified with longer-term bonds, slightly increasing its risk but adding an additional return source:

- **Term Factor**: Longer-term bonds yield higher returns as investors seek a premium for inflation risks.

Since these additional risk factors carry their own volatility and may temporarily underperform the broad market over several years, it's advisable to add them only as satellites—say, 20% of their respective portfolio part—to avoid [*tracking error regret*](https://www.core-wm.com/2019/08/01/what-is-tracking-error-regret/).

After setting these parameters, users will obtain a target allocation, as illustrated below.

<p align="center">
  <img src="Target Portfolio.png" alt="Exemplary Target ETF Portfolio" style="width:100%">
</p>
<p align="center">
  <i>Exemplary Target ETF Portfolio</i>
</p>

## Portfolio Tracking & Rebalancing

Users must input their total portfolio value, including new funds to be invested, and the amounts already invested in each ETF from their target allocation. The spreadsheet then identifies over- or under-investments in each ETF, aiding decisions on rebalancing or where to allocate the new funds.

## Sustainability (ESG)

Users can also choose to invest sustainably, but they need to understand what this entails:

Sustainable investing, also known as ESG (Environmental, Social, Governance) investing, aims to influence corporate investment decisions. If ESG-conscious investors avoid *sinful* companies—that is, those with poor environmental, social, and governance performance—these companies must offer a premium, i.e., higher expected returns, to attract investors, increasing their cost of capital.

The increased cost of capital means that fewer of these companies' investments will have a positive net present value (NPV), which in turn means that fewer environmentally harmful or socially irresponsible projects will be realized. This is the desired effect of sustainable investing.

You can read more about this [here](https://www.aqr.com/Insights/Perspectives/Virtue-is-its-Own-Reward-Or-One-Mans-Ceiling-is-Another-Mans-Floor).

For users who choose **ESG**, this means accepting potentially lower returns compared to also investing in *sinful* companies. Otherwise, there would be no real economic effect. Unfortunately, doing well by doing good is not always possible.

## Recommendations for Self-Education

To gain more insight, I recommend the [books by *Dr. Gerd Kommer*](https://gerd-kommer.de/buecher/) (German) or [*The Little Book of Common Sense Investing*](https://en.wikipedia.org/wiki/The_Little_Book_of_Common_Sense_Investing) by John Bogle, the father of indexing himself.

In my opinion, before reading any other book on finance, one should first familiarize oneself with passive investing. It not only provides a solid foundation from which to explore further topics but also instills a healthy skepticism right from the beginning, which is really necessary.
