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
