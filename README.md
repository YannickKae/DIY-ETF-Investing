# DIY ETF Investing

<p align="center">
  <img src="Target Portfolio.png" alt="Replication of the DAX with global Smart Beta / Factor ETFs" style="width:100%">
</p>
<p align="center">
  <i>Exemplary Target ETF Portfolio</i>
</p>

To simplify ETF portfolio set up, management and rebalancing for friends, I created the **Rebalancing Cockpit** *Excel* file, which is available here. I'm sharing it to inspire other DIY ETF savers/investors for their portfolio design.

## Target Portfolio

Users first need to set their target allocation, tweaking these parameters:

- **Age**: Your age implicitly dictates how much risk you can bear, especially if you're primarily saving for retirement. More time before retirement allows for riskier investments, as there's more time to recover from market downturns. In this portfolio model, the portfolio is split into a high-risk equity portion and a low-risk fixed income portion. Higher risk therefore means a larger equity allocation, computed by the following heuristic:

$$
\text{Equity Allocation} = \frac{100 - \text{Age}}{100}
$$

The high-risk equity portion can be further diversified with two primary risk factors / return sources, if desired:

- **Value Factor**: Cheaply valued companies (*value stocks*), as indicated by metrics such as the price-earnings ratio, tend to outperform highly valued companies (*growth stocks*).
- **Momentum Factor**: Companies with recent high returns tend to continue outperforming for a short period, and vice versa.

The fixed income portion can also be further diversified with longer-term bonds, slightly increasing its risk, but adding an additional return source.

- **Term Factor**: Longer-term bonds yield higher returns as investors seek a premium for inflation risks.

After setting these parameters, users get a target allocation, as illustrated above.

## Portfolio Tracking & Rebalancing

Users must input their total portfolio value, including new funds to be invested, and the amounts invested in each ETF from their target allocation. The spreadsheet then identifies over- or under-investments in each ETF, aiding decisions on rebalancing (reallocation) or where to allocate the new funds.

## Information

Additional theoretical background information about the portfolio elements is available on the second sheet of the Excel file, named *Information*.

Note that this portfolio model is based on ESG products, but that's not a necessity. The allocation logic elaborated above remains the same for non-ESG products.
