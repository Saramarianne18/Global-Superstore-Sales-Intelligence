# Global-Superstore-Sales-Intelligence
---

## Project Overview

For this project, I worked with the Global Superstore sales dataset and built an interactive Excel dashboard to surface business insights that management could actually use. The idea was straightforward — raw transaction data on its own tells you very little. My job was to shape it into something that answers real questions: which regions are driving revenue, where are we losing margin, and what does our customer base actually look like?

The end result is a dashboard that lets a non-technical stakeholder open Excel, apply a filter, and immediately see where the business stands.

---

## Objectives

- Understand sales and profit performance across regions and time
- Identify which product categories and customer segments contribute most
- Build a clean, interactive dashboard that non-technical users can navigate
- Translate the data into concrete business recommendations

---

## Tools Used

| Tool | Purpose |
|---|---|
| Microsoft Excel | Primary tool for data cleaning, analysis, and dashboard design |
| Pivot Tables | Summarising and slicing the data across multiple dimensions |
| Pivot Charts | Visualising patterns in a way that is easy to interpret |
| Slicers & Timeline | Making the dashboard interactive for end users |

---

## Dataset

The dataset covers real-world style retail transactions and includes fields like sales amount, profit, order quantity, customer segment, product category, shipping mode, region, and order date. It gave me enough breadth to look at the business from several angles — not just revenue, but profitability, customer mix, and operational trends.

---

## Data Cleaning

Before any analysis, I spent time getting the data into a reliable state. Steps I took:

- Converted the raw sheet into a structured Excel table so PivotTables could reference it cleanly
- Removed duplicate rows that would have inflated totals
- Checked every column for blanks and inconsistencies
- Verified that all numeric fields were formatted correctly for calculation
- Standardised date formats so the timeline slicer worked without issues

Skipping this step would have made every chart unreliable, so I treated it as a non-negotiable part of the process.

---

## Dashboard Components

| Analysis | Chart Type |
|---|---|
| Sales by Region | Clustered Bar Chart |
| Monthly Sales Trend | Line Chart |
| Profit by Category | Column Chart |
| Sales by Segment | Doughnut Chart |
| Top 5 Products | Horizontal Bar Chart |
| Sales vs Profit | Combo Chart |

I connected all charts to shared slicers and a timeline so a user can filter by year, region, or segment and every visual updates at once.

---

## What the Data Showed

**Regional Performance**
The Central region came out on top for sales. That gap between Central and the lower-performing regions is wide enough that it warrants a closer look at what is working there versus what is not being replicated elsewhere.

**Profitability by Category**
Technology products delivered the strongest profit margins by a clear margin. Furniture, on the other hand, moved volume but the profit story was much weaker — worth flagging for pricing and cost reviews.

**Customer Segments**
The Consumer segment accounted for the largest share of sales. Corporate and Home Office segments are present but underrepresent their potential given the order values they tend to carry.

**Product Mix**
A handful of products consistently punch above their weight on profit. There is an opportunity to lean into those more deliberately rather than spreading marketing effort evenly across the catalogue.

**Sales Trends**
Month-on-month sales are not flat — there are visible peaks and dips that suggest seasonal demand. A business planning around average monthly revenue is likely miscalculating at both ends of the year.

---

## SWOT Analysis

| Strengths | Weaknesses |
|---|---|
| Central region drives strong revenue | Profit margins are uneven across categories |
| Technology category is highly profitable | Some regions are consistently underperforming |
| Solid Consumer segment demand | Month-to-month revenue is not stable |

| Opportunities | Threats |
|---|---|
| Grow presence in high-performing markets | Rising competition in core segments |
| Double down on profitable product lines | Operational and shipping cost pressures |
| Better targeting of Corporate and Home Office segments | Broader market uncertainty |

---

## Insight Matrix

| Problem | What the Data Shows | Business Impact | Recommendation |
|---|---|---|---|
| Weak sales in certain regions | Regional breakdown highlights the gap | Drags down overall revenue | Targeted regional campaigns |
| Uneven profit margins | Sales vs Profit combo chart | Efficiency is being lost in low-margin lines | Revisit pricing strategy |
| Underperforming categories | Category-level profit analysis | Slows overall growth | Prioritise high-margin products |
| Unstable monthly revenue | Trend line across the year | Makes forecasting difficult | Introduce seasonal promotions |

---

## Recommendations

Based on what I found in the data, here is what I would suggest:

1. Invest more in the regions and channels that are already performing — scale what works before fixing what does not
2. Direct marketing budget toward the product categories with the highest profit margins, particularly Technology
3. Build a plan for the underperforming regions rather than treating them as a write-off
4. Review the cost structure around shipping — it is an area where margin is quietly being lost
5. Use the dashboard as a living tool, not a one-time report — it is built for ongoing monitoring
6. Pay more attention to the Corporate segment, which has room to grow

---

## Conclusion

This project gave me a practical end-to-end experience of what business analytics actually involves — not just building charts, but asking the right questions, cleaning the data properly, and making sure the output is useful to someone making decisions. The dashboard is not decorative; it is built to be used.

If I were presenting this to a leadership team, the conversation would not be about the visuals. It would be about the Central region, the Technology margin, and what is happening in the months where sales drop off. That is what the data is pointing to.

---

## Interview Questions

### Data-driven vs Intuition-based Decision Making

In practice, the framing of "data vs intuition" is a bit of a false choice. Data tells you what happened. It does not always tell you why, and it definitely does not make the decision for you.

Data-driven decisions are stronger when you have reliable, relevant data and enough time to analyse it. They reduce guesswork and give you something concrete to point to when explaining a decision to stakeholders.

Intuition-based decisions are faster and sometimes necessary — especially in situations where data is incomplete or a decision cannot wait. Experienced managers make good calls without a spreadsheet because they are drawing on pattern recognition built over years.

The best organisations use both. The analyst surfaces the data; the decision-maker brings judgment. Neither replaces the other.

---

### What is Impact Analysis?

Impact analysis is about thinking through consequences before committing to a decision. Before making a change — a pricing adjustment, a new campaign, a cost-cutting move — you ask: what happens downstream if we do this?

It covers financial effects, operational effects, customer effects, and risk. Done properly, it stops teams from solving one problem while quietly creating three others.

A simple example: if the business decides to cut the marketing budget to reduce costs, impact analysis would ask how much of current sales volume is marketing-driven, what happens to customer acquisition if spend drops, and whether the short-term saving is worth the long-term revenue risk. That kind of structured thinking is what separates reactive decisions from strategic ones.

---

## Skills Demonstrated

- Data cleaning and preparation in Excel
- PivotTable and PivotChart design
- Interactive dashboard development
- Business performance analysis
- Written communication of findings
- Strategic recommendation framing
