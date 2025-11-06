# Meta-Ads-Performance-Analysis (Interactive dashboard creation using Power BI)
## Project object
Built an interactive Power BI dashboard to monitor marketing campaign performance, track budget utilization efficiency, and analyze user engagement patterns to support data-driven decision-making.
## About the data:
This dataset represents Meta Ads Performance Data, covering campaigns, ads, user demographics, and ad interaction events. It is modelled after how Facebook/Instagram (Meta) ad platforms capture data.
The purpose of this dataset is to analyse advertising performance, optimize targeting, and measure ROI (Return on Investment) through KPIs such as:
- Impressions (how often ads are seen)
- Clicks (engagement with ads)
- Purchases (conversions)
- CPM, CPC, CTR, and ROAS (efficiency metrics)
- Audience insights (demographics, location, interests)

# Process
## 1. Data Preparation
- Collect advertising data from Kaggle (Facebook & Instagram).
- Clean data, handle missing values, reformat date data, money
- Create a Calendar table and reformat date columns to support time filtering.
## 2. Data Modeling
- Build a Star Schema including tables: ad_events, ads, campaigns, user (ad_events : fact table)
- Create DAX measures to calculate the main KPI:
- CTR = Clicks / Impressions
- CPC = Spend / Clicks
- Conversion Rate = Conversions / Clicks
- Engagement = [Clicks] + [Share] + Comment
- Purchase Rate = Purchase / Clicks
- Apply Selected Measure Value to flexibly compare multiple KPIs in the same chart
## 3. Visualization
- Design 2 separate dashboard pages:
- Facebook Performance: track advertising campaigns, impressions, CTR, CPC, conversions, etc.
- Instagram Performance: track similar performance, helping to compare the effectiveness between the two platforms.
- Use navigator buttons to smoothly switch pages.
- Add dynamic titles, cards, slicers (time, campaign, target interest) to help users interact and filter data quickly.
## 4. Insight 
- Strong awareness & engagement (high CTR & ER), but low purchase funnel efficiency : need better conversion strategy.
- Target audience: Females, 18–30, especially in India & Brazil.
- Best ad formats: Video > Stories > Carousel/Image.
- Timing: Schedule ads in the afternoon & evening slots.
- Budget Optimization: Shift more spend to high-performing geographies and ad formats.
- Action: Improve landing pages, offers, retargeting campaigns to lift purchase rate.
# Dasboard
![Dashboard 1](https://github.com/user-attachments/assets/c8086fc0-34f2-496d-8471-ca182fa1c24c)

![Dashboard 2](https://github.com/user-attachments/assets/8d67d4ff-ed06-40ff-8305-0eea2b825ac9)


