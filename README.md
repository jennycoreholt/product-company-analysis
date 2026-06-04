<p align="center">
<img alt="flourish health logo" width="300px" src="./images/flourish_health_logo.png">  
</p>

<h1 align="center">Flourish Health Probiotic Subscription<br> Product & Customer Analysis</h1>
<p align="center">
  Flourish Health is a Berlin-based probiotic subscription brand offering science-backed gut health products direct-to-consumer. This executive summary presents a data analysis take-home project examining three key business questions: the impact of pricing changes on customer behaviour, website engagement and funnel performance, and a demand forecast for a minimum order value gift promotion.
</p>

<p align="center">
  Documentation and work sheets are available on Google Spreadsheets <a href="https://docs.google.com/spreadsheets/d/17i_8Hc_iKhWiR3B0zZ6WxBPFd-McWYBPCIsJ-pXiVSY/edit?usp=sharing">here</a>.
</p>


<br>

## Table of Contents
1. [Impact of Pricing Change on Customer Behaviour](#Impact-of-Pricing-Change-on-Customer-Behaviour)
2. [Website Engagement & Conversion Funnel Analysis](#Website-Engagement-&-Conversion-Funnel-Analysis)
3. [Predicting demand for MOV gift 'New Product'](#Predicting-demand-for-MOV-gift)


<br>

## Impact of Pricing Change on Customer Behaviour
A pricing change was implemented in mid-August 2025, directly impacting a select customer segment. Prices were reverted to their original levels in mid-March 2026. The following analysis examines customer behaviour across three periods: pre, during, and post pricing change, to evaluate its overall effectiveness.

**Key Findings** 
<table>
  <tbody>
    <tr>
      <td width="50%">
        <img alt="customer purchases increased during the price change" src="./images/findings_1.png">  
      </td>
      <td>
        <b>Did the Pricing Change Affect Customer Behaviour?</b>
        Yes. Customer purchases rose significantly following the pricing change, increasing from 58% (pre) to 77% (during). A rise of 19 percent. Upon reversion to original pricing in mid-March, customer purchases declined to 68% (post), suggesting the changed price point was a direct driver of increased customer purchase engagement.
        <br>
        <br>
        <b>How Loyal Are Customers Acquired During the Pricing Change?</b>
        While higher engagement is a positive signal, for a subscription-based business, customer retention is a stronger indicator of long-term revenue health than initial engagement alone. This raises the question: did the pricing change attract loyal customers, or primarily price-sensitive ones?
      </td>
    </tr>
  </tbody>
</table>

<br>

**Deep Dive: Retention Rate Comparison** 
<table>
  <tbody>
    <tr>
      <td width="35%">
        Initial comparison of group averages suggested the "During" segment outperformed "Pre." However, this <b>result was misleading due to data imbalance across segments</b>. The "During" group contains significantly more cohorts, and later cohorts (Jan–Feb 2026) had insufficient months of data to produce reliable averages, artificially inflating the group's overall figure.
        <br>
        <br>
        To ensure a fair comparison, the following adjustments were made in the next step of the analysis:
        <br>
        <br>
        - Jan, Feb, and Mar 2026 cohorts were excluded due to insufficient data.
        - The Post segment was removed from comparative analysis for the same reason.
        - Analysis was narrowed to the first 3 months of retention, the longest period consistently available across both groups.
      </td>
      <td>
       <img alt="customer retention rates are consistently lower during the price change" src="./images/findings_2.png">   
      </td>
    </tr>
  </tbody>
</table>

<br>

**Findings: Months 1–3 Retention Comparison** 
<table>
  <tbody>
    <tr>
      <td width="55%">
         <img alt="relative impact between the different customer cohorts" src="./images/findings_3.png">   
      </td>
      <td>
        Examining the relative difference in retention rates between the Pre and During segments across comparable months reveals a clear picture:
        <br>
        <img alt="identifying the change difference %" src="./images/findings_4.png">  
        <br>
        The "Pre Price Change" segment consistently outperforms across every comparable month, confirming higher customer loyalty and retention in the pre price change group.
      </td>
    </tr>
  </tbody>
</table>

<br>
<br>

**Overall Retention Trend: Apr 2025 – Mar 2026**

![elist logo](./images/findings_5.png)  

<br>

A high-level view of **retention across all cohorts shows a gradual overall decline**, which is expected and not inherently negative. In a subscription business, this pattern typically reflects natural attrition, leaving the most loyal customers over time.

Notably, **retention increases every 3 months across cohorts**, consistent with a quarterly subscription cycle. This suggests customers are renewing on a 3-month basis, producing a recurring uplift in Month 3 retention figures across the dataset.

<br>

**Conclusion**
The **pricing change successfully drove higher engagement, but at the cost of customer quality**. Customers acquired during the pricing change showed consistently lower retention rates across all comparable months, suggesting the reduced price attracted price-sensitive customers rather than long-term loyal ones. For a subscription business, this represents a net negative outcome, as higher short-term volume does not offset lower long-term retention value. 

Rather than reducing the core subscription price, **sales and marketing stakeholders could test alternative models that lower the barrier to entry**, without devaluing the product, such as:

- Discounted first month with full-price renewal.
- Annual prepay discount (locks in commitment upfront).

<br>

## Website Engagement & Conversion Funnel Analysis
The following analysis examines website engagement metrics from April 2025 to March 2026, identifying key trends, drop-off points, and anomalies across the customer journey from session to web order.

**High-Level Conversion Performance**
The primary objective is to convert as many site sessions into web orders as possible. Benchmarked against global e-commerce standards (average: 1.65–3.0%, high performance: 3.5%+), the overall period performs well.

![high level conversions](./images/findings_6.png)

All months exceed the global average, indicating strong top-level conversion performance. May, September, and November are standout months. The drivers behind these peaks, whether promotional campaigns, seasonal demand, or marketing activity, warrant further investigation with the Sales and Marketing teams.

**Funnel Drop-Off Analysis: Where Are Users Lost?**

<table>
  <tbody>
    <tr>
      <td width="55%">
        <img alt="biggest drop off between add to cart and checkout" src="./images/findings_7.png">  
      </td>
      <td>
        Breaking the customer journey into its component stages reveals where the most significant drop-off occurs.
        <br>
        <br>
        <b>The Add to Cart → Checkout stage is the primary pain point in the funnel.</b> 
        <br>
        <br>
        Against an e-commerce benchmark of 50–70%, a 23% average conversion at this stage represents <b>a loss of approximately 77% of users who showed clear purchase intent. This level of drop-off strongly suggests friction</b> at the cart or checkout page, such as unexpected costs, a complicated checkout process, or trust barriers. This should be escalated to the Development team for a UX review of the cart page.
      </td>
    </tr>
  </tbody>
</table>

<br>

**Anomaly: Engaged Sessions → Add to Cart**
<table>
  <tbody>
    <tr>
      <td width="45%">
        Closer analysis of the Engaged Sessions → Add to Cart metrics reveals two significant positive outliers.
        <br>
        <br>
        September <b>(deviation +89% above average)</b> and November <b>(deviation +59% above average)</b> months saw a disproportionately high share of engaged visitors adding products to their cart. This suggests these visitors arrived with higher purchase intent than typical months. This could potentially be driven by a targeted campaign, a product launch, or an external referral. Understanding what drove behaviour in these two months could inform future marketing strategy.
        <br>
        <br>
        <b>Trend: Sharp Decline Dec 2025 – Mar 2026</b>
        <br>
        <br>
        Following the November peak, Engaged Sessions → Add to Cart dropped sharply <b>(difference -46.8% decline)</b> and sustained that decline through to March 2026.
        <br>
        <br>
        This nearly halved conversion rate over four consecutive months is the most significant trend in the dataset. Root cause investigation should involve Marketing, Sales, Operations, and Development to determine whether this was driven by pricing, seasonal factors, traffic quality changes, or product availability.
      </td>
      <td>
       <img alt="sharp decline in engaged sessions to add to carts from dec" src="./images/findings_8.png">  
      </td>
    </tr>
  </tbody>
</table>

<br>

**Corroborating Patterns**
![conversion patterns comparing all key metrics](./images/findings_9.png)

Two additional metric pairs display matching spike behaviour, reinforcing the above findings:

- Engaged Sessions → Add to Cart and Web Orders → Engaged Sessions 
**both spike in September and November**, confirming these months had unusually high-intent visitors throughout the entire funnel.

- Web Orders → Checkouts and Web Orders → Add to Cart 
**both spike in December and January**, suggesting that while fewer users were adding to cart in this period, those who did were more likely to complete their purchase. A smaller but more committed buyer pool

**Proposed Next Steps**
1. **Investigate the Add to Cart → Checkout drop-off:** prioritise a UX audit of the cart and checkout pages.

2. **Diagnose the September and November spikes:** cross-reference with marketing campaign data to identify what drove unusually high purchase intent in these months and replicate it.

3. **Investigate the Dec–Mar decline:** determine whether the drop in 'Add to Cart conversion' is linked to the pricing change, seasonal behaviour, or a shift in traffic quality.

<br>
<br>

## Predicting demand for MOV gift 'New Product'
Based on 13 months of historical data, product unit prediction was calculated for the 'New Product' for each month of 2026, 2027 and 2028. 33.75%
22.36%

![forecast for 2026, 20277 and 2028](./images/findings_10.png)

![highlighting inclining trend](./images/findings_11.png)

**Observations & Considerations**
- Seasonal indices are based **on a single year of observations.** 

- May and September spikes are treated as structural, as the task states these months are in-demand, but they could be one-off events.

- The trend (slope = 170 units/month) **is fitted on a mix of products with very different trajectories.** As a single-product forecast this assumes demand continues on the same aggregate path.

- Forecast **confidence degrades significantly beyond 12 months** given limited historical data.

- **No external factors** considered such as product popularity or price.

- The **low and high forecast were used to provide width** (breathing room) to the forcasted unit. **It's worth noting that 20% is an arbitary number**, used more as a placeholder, as it's wide enough to feel honest, yet small enough to provide a useful range. If more data is provided, the value can be adjusted accordingly.

![table of product demand predictions 2026 - 2028](./images/findings_12.png)
