<h1 align="center">TechGamer's sales Performance Report</h1>
<table align="center">
  <tr>
    <td width="1440">
      <h2 align="center">Client Background</h2>
      <body>
        <strong>TechGamer, founded in 2018, is a global retailer of new and refurbished gaming products. The company primarily sells through its online website, complemented by a mobile app, and leverages multiple marketing channels to reach and engage customers worldwide. With a customer base of approximately 21,000 active users and over 20,000 completed transactions, TechGamer generated $6.1 million in annual sales revenue over two years (2019-2021), recording the change in sales before and post-pandemic period. This project analyzes TechGamer’s sales data to uncover performance trends, product insights, and customer behavior patterns, providing actionable recommendations for business growth and strategic planning.<br>
      </body>
      <h3>Northstar Metrics</h3>
      <h4>
        <ul><li>Sales trends - Focusing on key metrics of sales revenue, number of orders placed, and average order value (AOV).</li>
          <li>Product performance - Analyzing different product lines, market impact, and refund rates to inform strategic product decisions.</li>
          <li>marketing evaluation - Evaluating the effectiveness of various marketing strategies and providing recommendations to maximize exposures to customers.</li>
          <li>Regional results - Evaluating regional demand and product performance within regions to identify areas for improvement.</li>
        </ul>
      </h4>
    </td>
  </tr>
</table>


<table align="center">
  <tr>
    <div width="920">
      <h1 align="center">Executive Summary</h1>
      <h3 align="center">Sales Revenue Analysis (2019–2021)</h3>
      <div align="center">
        <img width="1000" alt="Sales revenue graph from 2019 to 2022" src="https://i.postimg.cc/KjNFfkyb/Screenshot-2026-01-13-at-12-39-22.png" />
      </div>
      <td width="460" valign="top">
        <ol>
          <li>
            <strong>Revenue Growth and Peak Performance:</strong>
            <ul>
              <li>2020 was the strongest year, with sales consistently growing each quarter as a result of the COVID-19 pandemic.</li>
              <li>Q4 2020 saw the highest revenue ($1.25M in December 2020), making it the best-performing period.</li>
              <li>January 2021 ($1.03M) also maintained strong sales, though a downward trend started afterward.</li>
            </ul>
          </li>
          <li>
            <strong>Declining Trend in 2022</strong>
            <ul>
              <li>A sales anomaly and significant decline occurred in 2022, particularly in Q4, with October ($178K), November ($208K), and December ($262K) marking the lowest revenue months.</li>
              <li>The Q3 and Q4 revenue decline suggests a major downturn, likely caused by external market conditions, reduced consumer demand, or internal operational shifts.</li>
            </ul>
          </li>
        </ol>
      </td>
      <td width="460" valign="top">
        <ol start="3">
          <li>
            <strong>Quarterly Insights & Seasonal Trends</strong>
            <ul>
              <li>Q3 and Q4 of each year typically show strong performance, likely due to seasonal shopping trends and marketing efforts.</li>
              <li>Q1 2022 started well ($704K in January), but revenue quickly dropped, signaling an overall weak performance compared to previous years.</li>
            </ul>
          </li>
          <li>
            <strong>Key Takeaways & Recommendations</strong>
            <ul>
              <li>Investigate the causes of the 2022 decline (e.g., market changes, competition, internal factors).</li>
              <li>Leverage high-performing periods (e.g., Q3 and Q4 of strong years) to refine marketing and sales strategies.</li>
              <li>Reassess business strategy for 2023, focusing on pricing, promotions, and customer engagement to regain momentum.</li>
            </ul>
          </li>
        </ol>
      </td>
    </div>
  </tr>
</table>

<h2 align="center">Dataset Structure and ERD (Entity relationship diagram)</h2>
<body>The database structure as seen below consists of four tables: orders, customers, geo_lookup, and order_status, with a total row count of 10,8127 records.</body>
<div align="center">
  <img width="680" src="https://i.postimg.cc/Y0YRmp3M/Screenshot-2026-01-13-at-17-27-50.png">
</div>
<h1 align="center">Deep-Dive Insights</h1>
<table align="center">
  <tr>
    <h1 align="center">Sales Trend</h1>
    <td width="1000">
      <img width="300" src="https://i.postimg.cc/gJBXqDSD/Screenshot-2026-01-09-at-16-41-51.png">
    </td>
    <td width="1000">
      <img width="300" src="https://i.postimg.cc/FFwXdBg4/Screenshot-2026-01-09-at-16-51-30.png">
    </td>
    <td width="1000">
      <img width="300" src="https://i.postimg.cc/7h261yTb/Screenshot-2026-01-09-at-16-42-14.png">
    </td>
  </tr>
</table>


<table>
  <tr>
    <td>
      <strong>Sales Revenue</strong>
      <ol>
        <li>Sharp Decline in Q4 2022 – A Major Sales Anomaly <ul>
            <li>Historically, Q4 (Oct-Dec) has been the strongest quarter due to holiday shopping (Black Friday, Cyber Monday, Christmas sales). However, in 2022, <strong>Q4 sales plummeted</strong>. </li>
            <li>Sales in November 2022 reached a low of $178K, significantly below the $413K–$934K range observed in prior years. This represents a <strong>~57-81% drop</strong> from Q4 2021 and an even sharper decline compared to Q4 2020. </li>
          </ul>
        </li>
        <li>Post-Pandemic Sales Normalization (2020-2022 Trends) <ul>
            <li>2020 Sales Surge: The pandemic led to a significant boost in eCommerce sales, with Q2-Q4 2020 seeing a rapid increase (e.g., <strong>Q4 2020 was nearly double Q4 2019</strong>). </li>
            <li>2021 Slight Slowdown: Sales remained high but started stabilizing, showing a decline from peak pandemic levels.</li>
            <li>2022 Major Decline: A <strong>consistent drop in sales across all quarters</strong> suggests a post-pandemic correction, with inflation, lower consumer spending, or increased competition. </li>
          </ul>
        </li>
        <li>Declining Growth Throughout 2022 – Indicating Weak Consumer Demand <ul>
            <li>Each quarter in 2022 experienced a downward trend.</li>
            <li>Q1: Started fairly strong ($705K in Jan) but lower than 2021.</li>
            <li>Q2 - Q3: Dropped further, below $500K per month and continued decline through Q3 with Aug/Sep below $400K.</li>
            <li>Q4: <strong>Historic low, indicating critical demand issues</strong>. This suggests customer retention, pricing, or product-market fit issues. TechZone may need to re-strategize through marketing, promotions, or change in pricing. </li>
          </ul>
        </li>
      </ol>
      <strong>Average Order Value</strong>
      <ol>
        <li> Sharp AOV Surge in 2020, followed by a Decline in 2021-2022 <ul>
            <li>
              <strong>2020 saw the highest AOV growth, peaking at $321 (Oct 2020)</strong> compared to $246 (Nov 2019), aligning with pandemic-driven eCommerce boom.
            </li>
            <li>Post-pandemic correction (2021-2022) led to a steady decline, with AOV in 2022 returning close to 2019 levels (~$234-$237).</li>
          </ul>
        </li>
        <li>2022 AOV is lower and relatively more volatile compared to previous years <ul>
            <li>
              <strong>2022 AOV fluctuates significantly </strong> between $216 (Oct) and $256 (Sep).
            </li>
            <li>Q4 2022 AOV is significantly lower than Q4 2020 & 2021, meaning holiday spending per order has dropped.</li>
          </ul>
        </li>
        <li>Long-Term AOV Decline May Indicate Price Sensitivity <ul>
            <li>From a peak of ~$321 in 2020, AOV steadily dropped to ~$234 in 2022 which is 27% drop.</li>
            <li>Over the span of four years, the change in AOV growth has been relatively constant, indicating minimal changes in product pricing (as illustrated in Sales Growth vs. AOV Growth below).</li>
            <li>AOV in 2022 is likely not a major factor in the decline of sales that year.</li>
          </ul>
        </li>
      </ol>
      <strong>Order Count</strong>
      <ol>
        <li>Order counts closely follow sales revenue, indicating that the decline in revenue is primarily due to <strong>fewer orders</strong> rather than a drop in AOV in 2022. </li>
        <li>Total orders <strong>dropped by 40%</strong> from 2021 to 2022. </li>
        <li>The sales anamoly and decline <strong>started in mid-2022</strong>, with orders falling from 2,034 in July to just 825 in October. </li>
        <li>While people are spending slightly less per order, the <strong>decline in order frequency</strong> directly results in lower sales revenue. </li>
      </ol>
    </td>
  </tr>
</table>

<div align="center">
  <table>
    <tr>
      <h4>
        <strong>Sales Growth follows seasonal fluctuations, while AOV remains relatively constant, except for the Sales Growth in October 2022</strong>
      </h4>
      <td>
        <img width="700" alt="Sales Growth vs. AOV Growth" src="https://i.postimg.cc/q7K63P2t/Screenshot-2026-01-08-at-21-29-10.png" />
      </td>
    </tr>
  </table>
</div>
<table align="center">
  <tr>
     <h1 align="center">Product Performance</h1>
      <div align="center">
        <h3>Four Key Products Emerged as the Primary Drivers of Overall Sales Changes</h3>
        <img width="700" alt="Product sales graph from 2019 to 2022" src="https://i.postimg.cc/wvXF7jhf/Screenshot-2026-01-10-at-13-26-22.png" />
      </div>
    <tr>
  </tr>
</table>


<table aign="center">
  <tr>
      <td width="333" valign="top">
      <h3>The Best and Worst</h3>
      <ul>
        <li>The <strong>27 Inch 4K Gaming Monitor</strong> had consistently strong sales year over year totaling <strong>$9.85M</strong>, and it is the highest revenue generating product overall.</li>
        <li>Other best-performing products in terms of sales are <strong>Apple AirPods Headphones($7.74M)</strong>, <strong>MacBook Air Laptop($6.30M)</strong>, and <strong>Thinkpad Laptop($3.21M)</strong>.</li>
        <li>Other products accounted for minimal sales shares and had a negligible impact on overall sales.</li>
        
      
      
  <td width="333" valign="top">
      <h3>AOV Over Time</h3>
      <ul>
        <li>The AOV peaked in 2020 at $300.16 and then declined in 2021 ($254.71) and 2022 ($229.91).</li>
        <li>MacBook Air Laptop ($1,588), ThinkPad Laptop ($1,100), and Apple Iphone ($741) are the biggest contributors to AOV. </li>
        <li>Samsung Charging Cable Pack and Samsung Webcam have relatively low price points ($20.20 and $50.43 on average). They are stable but do not significantly impact AOV.</li>
        <li>AOV is trending downward, but mainly due to a decline of product sales.</li>
      </ul>
      </td>
      <td width="333" valign="top">
      <h3>Heat Map Findings</h3>
      <ul>
        <li>Consistent Q4 spikes, likely due to Black Friday, Cyber Monday, and the holiday shopping season.</li>
        <li>Biggest Q4 Performer: The <strong>27-inch 4K Gaming Monitor</strong>, <strong>Apple AirPods</strong> saw the biggest spikes.</li>
        <li>Overall, the green area highlights the best-performing periods. These periods, when analyzed at the product level, leverage further investigation and can provide valuable insights to help suggest future strategies.</li>
      </ul>
      </td>
</tr>
</table>
<table align="center">
    <tr align="center">
      <td width="1000" valign="top">
      <h3>AOV Exhibited Significant Fluctuations Among the Top Four Products (2019-2022)</h3>
      <img width="800" src="https://i.postimg.cc/RZ6wFyZs/Screenshot-2026-01-11-at-14-56-39.png">
    </td>
    <td width="1000">
      <h3>Product Sales Heat Map by Quarter</h3>
      <img width="450" src="https://i.postimg.cc/ryd0QyFk/Screenshot-2026-01-09-at-13-02-44.png">
    </td>
  </tr>
</table>


</table>
<table align="center">
  <tr>
    <h1 align="center">Loyalty Program Learnings</h1>
    <table align="center">
    <tr align="center">
      <td width="1000">
      <h3>Average Order Value by Loyalty Status</h3>
      <img width="450" src="https://i.postimg.cc/J42pSzj5/Screenshot-2026-01-09-at-13-11-02.png">
    </td>
    <td width="1000">
      <h3>Number of Orders by Loyalty Status</h3>
      <img width="450" src="https://i.postimg.cc/0ybx46Y4/Screenshot-2026-01-10-at-22-18-16.png">
    </td>
  </tr>
</table>


<table>
      <tr>
        <td>
          <ul>
            <li>Loyalty members have sustained AOV growth beyond the pandemic boom, with sales revenue increasing from $0.4M in 2019 to $2.7M in 2022 and an AOV growth rate of 18% from 2019 to 2022. Loyalty members continued to purchase higher-priced products and place more orders after the pandemic boom, up until August 2022.</li>
            <li>Non-loyalty members have not sustained sales revenue and AOV growth beyond the pandemic boom, with sales revenue decreasing from $3.4M in 2019 to $2.2M in 2022, along with an AOV decline of 8% during the same period.</li>
            <li>In 2022, loyalty members spent almost $31 more on average than non-loyalty members ($245 vs. $214). AOV for loyalty members has steadily increased year over year, climbing 1.1% from 2021, while non-loyalty members' AOV declined by 18.7%.</li>
            <li>Loyalty members outspend non-loyalty members on returning orders by nearly $60, whereas non-loyalty members have historically spent more on their first TechSphere orders.</li>
          </ul>
        </td>
      </tr>
    </table>
  </tr>
</table>
<table align="center">
  <h1 align="center">Refund Rates</h1>
  <tr>
    <td width="500">
       <div valign="top" align="center">
      <h3>Refund Rates Were Higher for High-Value Products, Particularly Laptops</h3>
      <img alt="Refund heat map of products" src="https://i.postimg.cc/5y2b75Fz/Screenshot-2026-01-11-at-11-46-37.png" />
    </div>
    </td>
    <td valign="top" width="500">
      <ul>
        <li>Laptops have the lowest retention rate, with the highest return rate year over year being the ThinkPad Laptop, followed by the MacBook Air Laptop.</li>
        <li>The least returned product is the Bose SoundSport Headphones, with a return rate of 0%, followed by the Samsung Charging Cable Pack, with an average return rate of 2%.</li>
        <li>However, the Bose SoundSport Headphones and the Samsung Charging Cable Pack ranks are the least frequently purchased product, in the bottom half of purchase orders.</li>
        <li>For 2022, there were no recorded returns for any product.</li>
      </ul>
    </td>
  </tr>
</table>
<table align="center">
  <h1 align="center">Regional Results</h1>
      <div align="center">
        <img width="600" alt="Sales by region" src="https://i.postimg.cc/CMcb5rPG/Screenshot-2026-01-09-at-12-14-52.png" />
      </div>
  <tr valign="top">
     <td width="900">
      <ul>
        <li>The North American region contributes the most to sales revenue for each TechZone product.</li>
          <ul>
            <li>An average of 52% of total sales per product.</li>
            <li>$2.7 million in 2022.</li>
          </ul>
        <li>In contrast, TechZone sales have underperformed in the Latin American region.</li>
          <ul>
            <li>Each product accounts for only an average of 6% of total sales.</li>
            <li>$256 thousand in 2022.</li>
          </ul>
        <li>Samsung Webcam see their highest sales rate in North America.</li>
          <ul>
            <li>58% of total sales occur in this region.</li>
          </ul>
        <li>The 27-Inch 4K Gaming Monitor is the most popular across products.</li>
          <ul>
            <li>Accounts for 35% of total product sales.</li>
          </ul>
        <li>Meanwhile, the Bose SoundSport Headphones are the least favored.</li>
          <ul>
            <li>Sales are close to 0% across products</li>
          </ul>
      </ul>
    </td>
  </tr>
</table>
<!-- <table>
  <tr>
    <td width="700" border="0"><h1>Recommendations</h1>
    <h4>Based on the uncovered insights, here are actionable items that TechZone can take away from our analysis.</h4></td>
    <td width="400" border="0"><div align="right">
      
    </div></td>
  </tr>
</table> -->
<table align="center">
    <h1>Recommendations</h1>
    <h4>Based on the uncovered insights, here are actionable items that TechZone can take away from our analysis.</h4>
      <ul>
        <h3>Sales</h3>
        <li>The consistent seasonal slowdowns observed in January and February suggest an opportunity to stabilize early-year revenue through increased marketing investment and targeted promotional campaigns during these low-demand periods.</li>
          <li>The sharp and anomalous decline in October 2022 (–31% growth rate), which marked the lowest revenue point across the four-year period, should be investigated in greater detail. Further analysis into pricing changes, customer behavior shifts, competitive pressures, or operational disruptions may help identify the root causes of this decline.</li>
          <li>The substantial drops in both sales and order volume during Q4 2022 (–48% and –47%, respectively), as well as the overall downturn in 2022, indicate broader structural challenges beyond seasonality. To reverse this trend, the company should reassess its pricing and promotional strategies, optimize the timing and effectiveness of campaigns, and strengthen customer engagement and retention initiatives.</li>
        <li>historical performance shows that Q3 and Q4 have been strong revenue-generating periods in prior years. Leveraging insights from these high-performing periods can help refine future marketing and sales strategies and support a more sustainable recovery heading into 2023.</li>
          <ul>
          </ul>
        <h3>Products</h3>
        <li>Optimize inventory for high-performing products year-round.</li>
          <ul><li>The 27-Inch 4K Gaming Monitor is the strongest product in terms of sales, approaching $10 million over four years.</li>
          <li>The Apple AirPods are also a strong-selling product, with close to $8 million in sales over four years.</li></ul>
        <li>Deprioritize inventory for low-performing products.</li>
          <ul><li>Bose SoundSport Headphones and Apple iPhone constitute for nearly 0% of total purchase orders.</li></ul>
        <li>Investigate sales for MacBook Air laptops.</li>
          <ul><li>MacBook Air Laptops rank third in sales revenue (22%) but fall in the bottom half for number of purchase orders (4%).</li></ul>
        <h3>Loyalty Program</h3>
        <li>Continue a strong push for the loyalty program to boost and stabilize sales, as loyalty members are more likely to return as customers and purchase high-priced items.</li>
          <ul><li> Loyalty Member AOV grew 18% from 2019 to 2022</li>
            <li>Loyalty members spent $31 more on average than non-loyalty members in 2022.</li></ul>
        <li>Offer incentives for loyalty members to target purchases of MacBook Air laptops.</li>
          <ul><li>Loyalty members align with the ideal user persona for MacBook Air laptops, as they purchase high-priced products, are more likely to return as customers, and rarely make returns.</li></ul>
        <h3>Refund Rates</h3>
        <li>Streamline product quality control for high AOV products as they are the most frequently returned products.</li>
          <ul><li>Macbook Air Laptops had an average return rate of 14% from 2019 to 2021.</li>
          <li>Thinkpad Laptops also had an average return rate of 14% from 2019 to 2021.</li></ul>
        <h3>Regions</h3>
        <li>Maximize market share in North America, as this region dominates sales across all TechZone products.</li>
          <ul><li>52% of product sales were in the North American region.</li></ul>
        <li>Diversify the portfolio in the Latin American region by expanding localized product offerings, sales channels, and market reach to increase sales revenue and purchase orders.</li>
          <ul><li>Only 6% of product sales were in the Latin American region.</li></ul>
        <li>Continue to streamline high-performing products.</li>
          <ul><li> The demand for the 27-inch 4K Gaming Monitor and Apple AirPods headphones remains high relative to the region.</li></ul>
      </ul>
</table>
