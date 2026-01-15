<h1 align="center">TechGamer's sales Performance Report</h1>
<table align="center">
  <tr>
    <td width="1440">
      <h2 align="center">Client Background</h2>
      <body>
        <strong>TechGamer, founded in 2018, is a global retailer of new and refurbished gaming products. The company primarily sells through its online website, complemented by a mobile app, and leverages multiple marketing channels to reach and engage customers worldwide. With a customer base of approximately 21,000 active users and over 20,000 completed transactions, TechGamer generated $6.1 million in annual sales revenue over two years (2019-2021), recording the change in sales before and post-pandemic period. This project analyzes TechGamer’s sales data to uncover performance trends, product insights, and customer behavior patterns, providing actionable recommendations for business growth and strategic planning.<br>
      </body>
      <h3>Metrics</h3>
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
      <h3 align="center">TechGamer Sales Show Sustained Growth Momentum Following 2020</h3>
      <div align="center">
        <img width="1000" alt="Sales revenue graph from 2019 to 2022" src="https://i.postimg.cc/KjNFfkyb/Screenshot-2026-01-13-at-12-39-22.png" />
      </div>
      <td width="460" valign="top">
        <ol>
          <li>
            <strong>Sustained Sales Growth Following 2020 Acceleration:</strong>
            <ul>
              <li>Overall, TechGamer demonstrates a strong upward sales trajectory across the timeframe. Monthly revenue remained relatively stable at a lower base in 2019, followed by a pronounced acceleration beginning in early 2020. From that point onward, sales consistently exceeded the historical average monthly revenue of $236.6K, indicating successful scaling of sales operations and sustained growth momentum.</li>
            </ul>
          </li>
          <li>
            <strong>Consistent Year-End Demand Drives Seasonal Peaks</strong>
            <ul>
              <li>Clear seasonality effects are evident in the data. Sales peak consistently during Q4, with December emerging as the strongest-performing month, while early-year months such as January and February tend to underperform relative to annual highs. This recurring pattern suggests that consumer demand is significantly influenced by year-end spending and promotional cycles.</li>
            </ul>
          </li>
        </ol>
      </td>
      <td width="460" valign="top">
        <ol start="3">
          <li>
            <strong>Seasonality Creates Both Upside and Planning Challenges</strong>
            <ul>
              <li>From a business perspective, these findings highlight the importance of seasonally informed planning. Predictable demand spikes create opportunities to optimize inventory allocation, marketing investment, and operational capacity, while softer periods present opportunities for targeted initiatives to stabilize revenue.</li>
            </ul>
          </li>
          <li>
            <strong>Recommendations to Maximize Peak-Season Performance</strong>
            <ul>
              <li>Prioritize marketing, inventory, and promotional efforts ahead of peak Q4 periods to maximize revenue capture.</li>
              <li>Implement targeted strategies during off-peak months to reduce revenue volatility.</li>
              <li>Incorporate observed seasonality patterns into sales forecasting and operational planning processes.</li>
            </ul>
          </li>
        </ol>
      </td>
    </div>
  </tr>
</table>

<h2 align="center">Dataset Structure and ERD (Entity relationship diagram)</h2>
<body>The database structure as seen below consists of four tables: orders, customers, and geo_lookup, with a total row count of 10,8127 records.</body>
<div align="center">
  <img width="680" src="https://i.postimg.cc/Y0YRmp3M/Screenshot-2026-01-13-at-17-27-50.png">
</div>
<h1 align="center">Deep-Dive Insights</h1>
<table align="center">
  <tr>
    <h1 align="center">Sales Trend</h1>
    <td width="1000">
      <img width="300" src="https://i.postimg.cc/RVyG0XnP/Screenshot-2026-01-14-at-15-51-12.png">
    </td>
    <td width="1000">
      <img width="300" src="https://i.postimg.cc/Qxxv74C5/Screenshot-2026-01-14-at-15-49-18.png">
    </td>
    <td width="1000">
      <img width="300" src="https://i.postimg.cc/9X1ncdpg/Screenshot-2026-01-14-at-15-49-57.png">
    </td>
  </tr>
</table>


<table>
  <tr>
    <td>
      <strong>Sales Revenue</strong>
      <ol>
        <li>Strong Post-2020 Revenue Acceleration <ul>
            <li>Total sales demonstrate a clear upward trajectory across the timeframe, with a pronounced acceleration beginning in early 2020. </li>
            <li>Following this inflection point, monthly revenue consistently exceeds the historical average of $228K, indicating successful scaling of sales operations. </li>
          </ul>
        </li>
        <li>Concentrated Year-End Revenue Peaks <ul>
            <li>Sales peak consistently toward the end of each year, with December emerging as the strongest-performing month, reaching a high of approximately $549K. </li>
            <li>This recurring pattern suggests that overall revenue performance is significantly influenced by year-end demand cycles.</li>
          </ul>
        </li>
        <li>Data Coverage Consideration <ul>
            <li>The decline observed in early 2021 should be interpreted with caution due to incomplete data availability, rather than as a confirmed downward trend.</li>  
          </ul>
        </li>
      </ol>
      <strong>Average Order Value</strong>
      <ol>
        <li> Gradual Improvement in Average Order Value <ul>
            <li>
              Average Order Value (AOV) shows a steady upward trend, rising from the low-to-mid $200 range in 2019 to consistently above $300 in later periods.
            </li>
            <li>A temporary dip in early 2020 (approximately $227) is followed by a sustained recovery, suggesting improvements in pricing, product mix, or customer purchasing behavior.</li>
          </ul>
        </li>
        <li>AOV as a Supporting Revenue Driver <ul>
            <li>
              AOV remains above the historical average of $261 for most of the post-2020 period, contributing positively to overall revenue growth alongside rising order volume.  
          </ul>
        </li>
      </ol>
      <strong>Order Count</strong>
      <ol>
        <li> Expanding Transaction Volume <ul>
            <li>
              Order count increases substantially over time, reflecting growing customer demand and higher transaction activity.
            </li>
            <li>Post-2020 order volumes remain consistently above the historical average of 810 orders, indicating sustained demand momentum.</li>
          </ul>
        </li>
        <li> Seasonal Spikes in Order Activity <ul>
            <li>
              Order volumes peak during year-end periods, with monthly highs reaching approximately 1,671 orders, reinforcing the presence of strong seasonal purchasing behavior.
            </li>
          </ul>
        </li>
      </ol>
    </td>
  </tr>
</table>

<div align="center">
  <table>
    <tr>
      <h4>
        <strong>Sales Growth follows seasonal fluctuations, while AOV remains relatively constant
      </h4>
      <td>
        <img width="700" alt="Sales Growth vs. AOV Growth" src="https://i.postimg.cc/PfmZ8DqG/Screenshot-2026-01-14-at-19-06-50.png" />
      </td>
    </tr>
  </table>
</div>
<table align="center">
  <tr>
     <h1 align="center">Product Performance</h1>
      <div align="center">
        <h3>Four Key Products Emerged as the Primary Drivers of Overall Sales Changes</h3>
        <img width="700" alt="Product sales graph from 2019 to 2022" src="https://i.postimg.cc/CLq28mqy/Screenshot-2026-01-14-at-19-12-48.png" />
      </div>
    <tr>
  </tr>
</table>


<table aign="center">
  <tr>
      <td width="333" valign="top">
      <h3>The Best and Worst</h3>
      <ul>
        <li>Total sales are dominated by a limited number of core products, with the 27-inch 4K gaming monitor generating close to $2.0M in cumulative revenue, making it the single largest contributor.</li>
        <li>The Nintendo Switch and Sony PlayStation 5 Bundle each contribute approximately $1.5M–$1.7M in total sales, forming a clear second tier of high-impact products.</li>
        <li>In contrast, remaining products—including gaming accessories—contribute only a small fraction of total revenue, creating a pronounced long-tail distribution.</li>
      </ul>
        
        
      
      
  <td width="333" valign="top">
      <h3>Core Products Maintain Distinct and Stable AOV Bands</h3>
      <ul>
        <li>The Sony PlayStation 5 Bundle consistently maintains the highest AOV, fluctuating around $1.5K–$1.7K, reflecting its premium positioning.</li>
        <li>Across products, AOV levels remain relatively stable over time, with fluctuations largely confined within established price bands. </li>
        <li>This stability suggests that changes in total revenue are driven primarily by order volume, rather than significant shifts in pricing strategy or discount intensity.</li>
      </ul>
      </td>
      <td width="333" valign="top">
      <h3>Demand Growth Is Concentrated in a Few High-Volume Products</h3>
      <ul>
        <li>The Nintendo Switch exhibits the strongest growth in order volume, with monthly orders rising from roughly 200–300 in 2019 to peaks exceeding 700 orders in later periods.</li>
        <li>High-volume products such as the Nintendo Switch drive revenue primarily through order count expansion, despite lower AOV.</li>
        <li>In contrast, premium products like the PlayStation 5 Bundle generate revenue through high AOV with lower transaction volumes, reflecting different demand mechanics.</li>
      </ul>
      </td>
</tr>
</table>
<table align="center">
    <tr align="center">
      <td width="1000" valign="top">
      <h3>Average Order Value (AOV) by Product Over Time</h3>
      <img width="800" src="https://i.postimg.cc/DwY5YGsg/Screenshot-2026-01-14-at-19-17-50.png">
    </td>
    <td width="1000">
      <h3>Order Count by Product Over Time</h3>
      <img width="450" src="https://i.postimg.cc/W4Lq3bPV/Screenshot-2026-01-14-at-19-21-48.png">
    </td>
  </tr>
</table>


</table>
<table align="center">
  <tr>
    <h1 align="center">Marketing Channel Performance Insights</h1>
    <table align="center">
    <tr align="center">
      <td width="1000">
      <h3>Direct Channel Is the Primary Driver of Overall Sales Growth</h3>
      <img width="450" src="https://i.postimg.cc/8c3f6xCw/Screenshot-2026-01-14-at-22-12-12.png">
    </td>
    <td width="1000">
      <h3>Direct Channel Consistently Drives Sales Across Core Products</h3>
      <img width="550" src="https://i.postimg.cc/zvDF7m8L/Screenshot-2026-01-14-at-22-10-25.png">
    </td>
  </tr>
</table>


<table>
      <tr>
        <td>
          <ul>
            <li>The direct channel dominates total sales performance, contributing the vast majority of revenue across the entire timeframe, rising from below $150K per month in 2019 to peaks exceeding $400K during high-demand periods. This strong upward trend indicates that overall revenue growth is primarily driven by direct customer engagement, rather than reliance on third-party channels.</li>
            <li>Email emerges as the strongest secondary channel, showing steady growth over time and reaching monthly sales in the $40K–$60K range during peak periods.</li>
            <li>Heavy reliance on the direct channel creates a strong revenue foundation but also increases exposure to disruptions in direct traffic or conversion.</li>
            <li>Across all major products—including the 27-inch 4K gaming monitor, Nintendo Switch, Lenovo IdeaPad Gaming 3, and Sony PlayStation 5 Bundle—the direct channel remains the dominant source of sales. This consistency suggests that channel effectiveness is structural rather than product-specific.</li>
          </ul>
        </td>
      </tr>
    </table>
  </tr>
</table>

<table align="center">
  <tr>
    <h1 align="center">Regional Performance Insights</h1>
    <table align="center">
    <tr align="center">
      <td width="1000">
      <h3>North America Is the Primary Growth Engine Across the Timeframe</h3>
      <img width="450" src="https://i.postimg.cc/kG02vLx9/Screenshot-2026-01-15-at-11-49-56.png">
    </td>
    <td width="1000">
      <h3>Core Products Perform Consistently Across Regions, Led by North America</h3>
      <img width="550" src="https://i.postimg.cc/sxhXxKtV/Screenshot-2026-01-15-at-11-50-45.png">
    </td>
  </tr>
</table>


<table>
      <tr>
        <td>
          <ul>
            <li>North America (NA) consistently generates the highest sales among all regions, rising from approximately $60K–$80K per month in 2019 to peaks exceeding $250K during high-demand periods. This sustained outperformance indicates that overall sales growth is largely driven by demand expansion in the North American market.</li>
            <li>EMEA shows steady and meaningful growth over time, with monthly sales increasing from roughly $30K–$50K in 2019 to peaks near $180K–$190K.</li>
            <li>Across all major products, North America remains the dominant region, consistently contributing the largest share of product-level sales.</li>
          </ul>
        </td>
      </tr>
    </table>
  </tr>
</table>









<!-- <table>
  <tr>
    <td width="700" border="0"><h1>Recommendations</h1>
    <h4>Based on the uncovered insights, here are actionable items that TechGamer can take away from our analysis.</h4></td>
    <td width="400" border="0"><div align="right">
      
    </div></td>
  </tr>
</table> -->
<table align="center">
    <h1>Recommendations</h1>
    <h4>Based on the uncovered insights, here are actionable items that TechGamer can take away from our analysis.</h4>
      <ul>
        <h3>Sales</h3>
        <li>Incorporate observed Q4 demand peaks into annual sales forecasting, inventory planning, and operational resourcing to fully capture high-demand periods.</li>
          <li>Proactively address early-year softness through targeted promotions, pricing incentives, or bundled offerings to reduce revenue volatility outside peak seasons.</li>
          <li>Use historical seasonality patterns as a baseline for capacity planning, rather than applying uniform monthly targets across the year.</li>
          <ul>
          </ul>
        <h3>Products</h3>
        <li>Protect Flagship Products While Reducing Concentration Risk</li>
          <ul><li>Prioritize inventory availability, supply chain resilience, and pricing discipline for core revenue-driving products, including the 27-inch 4K gaming monitor, Nintendo Switch, and PlayStation 5 Bundle.</li>
          <li>The Apple AirPods are also a strong-selling product, with close to $8 million in sales over four years.</li>
          <li>Develop complementary or adjacent product offerings to gradually diversify revenue sources, reducing overreliance on a small number of flagship products.</li></ul>
        <li>Apply product-specific strategies based on revenue drivers:</li>
          <ul><li>High-volume products: focus on availability and fulfillment efficiency.</li>
          <li>High-AOV products: protect margins and premium positioning.</li></ul>
        <h3>Marketing Channel</h3>
        <li>Continue to invest in and optimize the direct channel, which is the primary driver of sales growth across products and regions.</li>
        <li> Expand the role of email marketing as a reliable secondary channel, particularly for repeat purchases and targeted campaigns during off-peak periods.</li>
            <li>Reassess affiliate and social media strategies to identify product- or region-specific use cases, rather than expecting uniform performance across the portfolio.</li>
        <li>Establish channel-level performance benchmarks to monitor concentration risk and guide diversification efforts.</li>
          <h3>Region</h3>
        <li>Maintain strategic focus on North America, which serves as the primary growth engine across products and channels.</li>
          <li>Continue scaling EMEA as a strong secondary market, leveraging its consistent alignment with overall demand trends.</li>
          <li>Thinkpad Laptops also had an average return rate of 14% from 2019 to 2021.</li>
          <li>Adopt a selective, product-led approach in APAC and LATAM, prioritizing products that already show early traction rather than broad regional expansion.</li>
          <li>Avoid one-size-fits-all regional strategies; instead, tailor go-to-market approaches by region–product combination.</li>
      </ul>
</table>
