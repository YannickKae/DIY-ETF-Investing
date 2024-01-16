# DIY ETF Investing

<p align="center">
  <img src="Target Portfolio.png" alt="Replication of the DAX with global Smart Beta / Factor ETFs" style="width:100%">
</p>
<p align="center">
  <i>Exemplary Target ETF Portfolio</i>
</p>

To simplify ETF portfolio set up, management and rebalancing for friends, I created the **Rebalancing Cockpit** *Excel* file, which is available here. I'm sharing it to inspire other DIY ETF savers/investors for their portfolio design.

## Target Portfolio

### Level 1 Allocation

Users first need to set their target allocation, tweaking these parameters:

- **Age**: Your age implicitly dictates how much risk you can bear, especially if you're primarily saving for retirement. More time before retirement allows for riskier investments, as there's more time to recover from market downturns. In this portfolio model, the portfolio is split into a *high-risk* equity portion and a *low-risk* fixed income portion. Higher risk therefore means a larger equity allocation, computed by the following heuristic:

$$
\text{Equity Allocation} = \frac{100 - \text{Age}}{100}
$$

More professionally, the question of how volatile a portfolio can be designed is embedded in a multi-factorial optimization problem that includes long-term liabilities, short-term liquidity, investment horizon & risk contraints. As said above, this is a heuristic for DIY investors.

### Level 2 Allocation

The **high-risk equity portion** can be further diversified with two primary risk factors / sources of return, if desired:

- **Value Factor**: Cheaply valued stocks (*value stocks*), as indicated by metrics such as the price-earnings ratio, tend to outperform highly valued stocks (*growth stocks*).
- **Momentum Factor**: Stocks with recent high returns tend to continue outperforming for a short period, and vice versa.

The fixed income portion can also be further diversified with longer-term bonds, slightly increasing its risk, but adding an additional return source.

- **Term Factor**: Longer-term bonds yield higher returns as investors seek a premium for inflation risks.

Since these additional risk factors / sources of return carry their own volatility and may temporarily underperform the broad market over several years, it is advisable to add them only as satellites, say 20% of their respective portfolio part, to avoid [*tracking error regret*](https://www.core-wm.com/2019/08/01/what-is-tracking-error-regret/).

After setting these parameters, users get a target allocation, as illustrated above.

## Portfolio Tracking & Rebalancing

Users must input their total portfolio value, including new funds to be invested, and the amounts invested in each ETF from their target allocation. The spreadsheet then identifies over- or under-investments in each ETF, aiding decisions on rebalancing (reallocation) or where to allocate the new funds.

## Sustainability (ESG)

Users can also choose to invest sustainably, but they need to be aware of what it means:

Sustainable investing, also known as ESG (Environmental, Social, Governance) investing, is supposed to affect corporate investment decisions. If ESG-conscious investors avoiding *sinful* companies, i.e. those with poor environmental, social and governance performance, those companies must offer apremium, i.e. higher expected returns to attract investors, increasing their cost of capital.
The increased cost of capital means that fewer of these companies' investments will have a positive net present value (NPV), which in turn means that fewer environmentally harmful or socially irresponsible projects will be realized. This is the desired effect of sustainable investing. More in this [here](https://www.aqr.com/Insights/Perspectives/Virtue-is-its-Own-Reward-Or-One-Mans-Ceiling-is-Another-Mans-Floor).

For users who choose ESG, this means accepting potentially lower returns compared to investing in *sinful* companies. Otherwise, there would be no real economic effect. Doing well by doing good is unfortunately not possible.

## Recommendations for Self-Education

To get more insight, I highly recommend the [books by *Dr. Gerd Kommer*](https://gerd-kommer.de/buecher/) (German) or The [*Little Book of Common Sense Investing*](https://en.wikipedia.org/wiki/The_Little_Book_of_Common_Sense_Investing) by John Bogle, the father of Indexing himself. In my opinion: Before reading any other book on finance, one should first familiarize oneself with passive investing, as it not only provides a good foundation from which to explore other topics, but also instills a healthy skepticism from the beginning, which is really necessary in the retail investment business.
