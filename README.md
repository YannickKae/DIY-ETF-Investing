# DIY ETF Investing

<p align="center">
  <img src="Target Portfolio.png" alt="Replication of the DAX with global Smart Beta / Factor ETFs" style="width:100%">
</p>
<p align="center">
  <i>Exemplary Target ETF Portfolio</i>
</p>

In order to simplify the process of managing and rebalancing my friends' ETF portfolios, I created the **Rebalancing Cockpit** Excel file, which can be found here, and which I would like to share with other *DIY ETF savers/investors* for inspiration.

## Target Portfolio

First, the user has to determine his target allocation, where the following parameters can be varied:

- **Age**: In general, the current age determines how much time an investor has left, assuming that financial planning is primarily for retirement. The older an investor is, the more risky/more volatile he can invest, as he has more time to patiently ride out temporary market downturns. In this case, we split the portfolio into a high-risk equity component and a low-risk bond component. More risk therefore means a higher equity component, using the following heuristic

$$
\text{Equity Allocation} = \frac{100 - \text{Age}}{100}
$$

If desired, the high-risk equity component can be diversified by the following two main risk/return sources:

- **Value Factor**: Companies that are cheaply valued (*value stocks*) - as measured by business metrics such as price-earnings ratios - tend to have higher returns than highly valued companies (*growth stocks*).
- Momentum Factor**: Companies that have recently generated relatively high returns tend to continue to generate higher returns for a limited period of time, and vice versa.

If desired, longer-term bonds can be added to the bond portion, making the low-risk bond portion of the portfolio somewhat riskier. Nevertheless, this is an overall diversifying source of return.

- Term Factor**: Longer-term bonds offer higher returns because investors demand a premium for bearing the risk of unexpected inflation.

After setting these parameters, the user will receive a target allocation as shown in the figure above.

## Portfolio Tracking & Rebalancing

Here, the user is asked to enter how much of his portfolio, including the new funds to be invested, and how much is invested in each of the ETFs corresponding to the portfolio elements of the target allocation. They are then shown which ETFs they have too much or too little invested in and can decide whether they want to rebalance, i.e. make purchases and sales, or which ETF they want to invest their monthly savings installment in.

## Information

The second sheet in the Excel spreadsheet, labeled *Information*, provides more theoretical background on the portfolio elements.

It is important to note that this is an ESG portfolio that can be replaced by non-ESG ETFs. The allocation considerations remain the same.

Um Freunden zu erleichtern, ihr ETF-Portfolio zu besparen und zu rebalancen, habe ich ich ihnen die hier zu findende Excel-Datei *Rebalancing Cockpit* erstellt, welche ich heirmit zur Inspiration für andere DIY ETF-Sparer/Investoren zur Verfügung stellen will.

## Target Portfolio

Zunächst muss der Nutzer seine Target Allokation bestimmmen, wobei wogende Paramater variierbar sind:

- **Age**: Das aktuell Alter bestimmt in der Regel, sofern primär für den Lebensabend finanziell vorgesorgt wird, wie viel Zeit ein Investor mitbringt. Je mehr, desto riskanter/volatiler kann er investieren, da er mehr Zeit bringt, temporäre Markt-Einbrüche, in Folge des sich manifestierendes Risiko, geduldig auszusitzen. Im hiesigen Fall separieren wir das Portfolio in einen risiko-reichen Aktien-Anteil und in einen risiko-armen Anleihen-Anteil. Mehr Risiko bedeutet somit ein höherer Aktien-Anteil, wobei wie folgende Heuristik anwenden:

$$
\text{Equity Allocation} = \frac{100 - \text{Age}}{100}
$$

Der risiko-reiche Aktien-Anteil lässt sich, falls gewünscht, um die beiden wichtigsten folgenden Risiko-Faktoren / Rendite-Quellen diversifizieren:

- **Value Factor**: Companies that are cheaply valued (*value stocks*) - as measured by business metrics such as price-earnings ratios - tend to have higher returns than highly valued companies (*growth stocks*).
- *Momentum Factor**: Companies that have recently had relatively high returns tend to continue to have higher returns for a limited period of time, and vice versa.

Auch der Anleihen-Anteil lässt sich, falls gewünscht, mit längerfristgen Anleihen augmentieren, wobei diese den risiko-armen Anleihen-Teil des Portfolio etwas riskanter gestalten. Dennoch handelt es sich dabei um eine insgesamt diversifizierende Rendite-Quelle.

- **Term Factor**: Longer term bonds provide hiehr returns, because Investors demand a premium for bearing the risk of unexpected inflation.

Nach Spezifikation dieser Paramater, erhält der Nutzer eine Target Allokation, wie sie in der obigen Abbildung zu sehen ist.

## Portfolio Tracking & Rebalancing

Hier muss der Nutzer eingeben, wie viel sein Portfolio, inklusive der neu zu ivestierenden Gelder umfasst und wie viel jeweils in die den Portfolio-Elementen der Target Allokation entsprechenden ETFs investiert ist. Daraufhin wird ihm angezeigt, in welhen ETFs zu viel bzw. zu wenig investiert ist und kann so entscheiden, ob er Rebalancen, d.h. Ab- & Zuverkäufe tätigen will, oder in welchen ETF er seine monatiche Sparrate Investieren möchte.

## Informations

Auf dem zweiten Sheet innerhalb des Excel Spreadsheets, namens *Informations* sind weitere theorerischen Hintergrund-Informationen zu den Portfolio-Elementen zu finden.

Wichtig ist, dass es sich hierbei um ein ESG-Portfolio handelt, welche auch durch Nicht-ESG ETFs substituiert werden können. Die Allokations-Überlegungen bleiben die Gleichen.
