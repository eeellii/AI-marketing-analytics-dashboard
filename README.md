# AI Marketing Analytics Agent

Natural Language Question  
↓  
LLM Analysis Planner  
↓  
Dynamic Pandas Execution  
↓  
Business Metrics  
↓  
LLM Insight Generation  
↓  
Actionable Recommendations


## Project Overview

This project is an AI-assisted marketing analytics workflow prototype inspired by real-world social media and e-commerce operations.

The system combines:

- Python (Pandas)
- OpenAI API
- Automated business insight generation
- Marketing performance analysis

to help analyze sales and campaign data more efficiently.

---

## Business Goal

The goal of this project is to automate parts of the marketing analytics workflow, including:

- Channel performance analysis
- Neighborhood and regional sales analysis
- Product category analysis
- AI-generated business insights

Instead of manually summarizing reports, the workflow uses LLM-assisted insight generation to support faster business decision-making.

---

## Technologies Used

- Python
- Pandas
- Jupyter Notebook
- OpenAI API
- Plotly
- python-dotenv

---

## Example Questions

- Which neighborhood generated the highest total sales?

- Which product category has the highest average order value?

- Which customer segment contributes the most revenue?

- Which season shows the strongest sales performance?

- What growth opportunities can be identified from the sales data?

---

# Current Version

### V1 – Rule-Based Analytics
- Fixed analysis routes
- Basic business insight generation

### V2 – Automated Business Reporting
- Marketing Report generation
- Growth Report generation
- E-commerce Report generation
- Automated KPI summaries

### V3 – AI Analytics Agent
- Understands natural language questions
- Creates analysis plans automatically
- Executes Pandas aggregations dynamically
- Generates AI-powered business insights
- End-to-end workflow through a single function:
```python
ask_data(
    "Which neighborhood generated the highest total sales?"
)
```
Example Output

Analysis Plan:
{
  "group_by": "neighborhood",
  "metric": "order_amount",
  "aggregation": "sum"
}

Analysis Result:
Fenway        37730.66
Cambridgeport 36657.22

AI Insight:
1. Fenway generated the highest sales.
2. Strong demand is concentrated in several neighborhoods.
3. Consider increasing marketing investment in top-performing regions.
   
---

## Disclaimer

This project uses synthetic/demo business data inspired by real-world analytics workflows. No private company data is included.
