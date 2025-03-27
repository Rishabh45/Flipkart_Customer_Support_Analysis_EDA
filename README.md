<h1 style="text-align: center;">Flipkart Customer Support Analysis</h1>
<p align="center">
  <img src="https://github.com/Rishabh45/Flipkart_Customer_Support_Analysis_EDA/blob/main/flipkart_logo.png" width="700" height="400">
</p>

---
### Project Overview
In the competitive e-commerce landscape, exceptional customer service is vital for growth and loyalty. This project conducts an **Exploratory Data Analysis (EDA)** on Flipkart's customer support data, focusing on interactions, feedback, and satisfaction scores across multiple channels. The goal is to identify key factors influencing customer satisfaction, evaluate support team performance, and propose actionable strategies to optimize the customer experience.

**Contributor:** Rishabh Kumar

**Type:** Individual Project

**GitHub Repository:** [Flipkart_Customer_Support_Analysis_EDA](https://github.com/Rishabh45/Flipkart_Customer_Support_Analysis_EDA) <br><br>

---
### Problem Statement
Flipkart handles a high volume of customer queries daily, yet challenges like delayed responses, unresolved issues, and inconsistent satisfaction levels persist. This analysis aims to:
- Identify common complaint categories.
- Assess response times and their impact on CSAT scores.
- Evaluate agent performance and support channel effectiveness.
- Uncover patterns driving satisfaction levels. <br><br>

---
### Objectives
Flipkart handles a high volume of customer queries daily, yet challenges like delayed responses, unresolved issues, and inconsistent satisfaction levels persist. This analysis aims to:
- **Enhance CSAT Scores:** Pinpoint factors lowering satisfaction and implement improvements.
- **Optimize Resolution Efficiency:** Streamline workflows for faster issue resolution.
- **Boost Agent Performance:** Improve training and workload management.
- **Reduce Support Costs:** Automate repetitive tasks and optimize resources.
- **Enable Data-Driven Decisions:** Leverage analytics for proactive support strategies. <br><br>

---
### Dataset Details
- **Source:** [Customer_support_data.csv](https://raw.githubusercontent.com/Rishabh45/Flipkart_Customer_Support_Analysis_EDA/refs/heads/main/Customer_support_data.csv)

- **Size:** 85,907 rows, 20 columns
  
- **Key Columns:**
  - `CSAT Score` **:** Customer satisfaction rating (1-5).
  - `channel_name` **:** Support channel (e.g., chat, email, phone).
  - `category` **&** `Sub-category` **:** Issue type.
  - `Issue_reported at` **&** `issue_responded` **:** Timestamps for response time analysis.
  - `Agent_name, Agent Shift` **:** Agent performance metrics.

- **Missing Data:** Notable in `Customer Remarks` (33%), `order_date_time` (80%), and `connected_handling_time` (99%). <br><br>

---
### Technologies Used
- **Python:** Core programming language
  
- **Libraries:**
  - `pandas` **&** `numpy` **:** Data manipulation
  - `matplotlib` **&** `seaborn` **:** Visualizationchannel_name:` Support channel (e.g., chat, email, phone).
  - `IPython.display` **:** Enhanced output formatting

- **Environment:** Jupyter Notebook. <br><br>

---
### Key Insights
- **CSAT Distribution:** Scores concentrate between 2-5, peaking at 3-4, with outliers below 0 and above 8.
- **Pain Points:** Refunds, returns, and cancellations yield the lowest CSAT scores and highest complaint frequency.
- **Response Time Impact:** Longer response and resolution times strongly correlate with lower CSAT scores.
- **Agent Performance:** Evening shift agents show lower satisfaction ratings, indicating training or staffing gaps.
<p align="center">
  <img src="https://github.com/Rishabh45/Flipkart_Customer_Support_Analysis_EDA/blob/main/CSAT%20Score%20Distribution.PNG" width="800" height="400">
</p>
<p><b>Observation: </b>
<ul>
  <li>The distribution of Customer Satisfaction (CSAT) scores is highly skewed, with the majority of ratings concentrated at 5.0 and a smaller peak at 1.0.</li>
  <li>There are significantly fewer responses for middle-range scores (2.0 and 3.0), indicating that customers tend to either be very satisfied or very dissatisfied rather than neutral.</li>
  <li>The high peak at 5.0 suggests that most customers are highly satisfied, while the smaller peak at 1.0 indicates a notable group of dissatisfied customers, highlighting a polarized customer experience.</li>
</ul>
</p> <br><br>

---
### Usage Instructions
**1. Clone the Repository:** `git clone https://github.com/Rishabh45/Flipkart_Customer_Support_Analysis_EDA.git`
  
**2. Install Dependencies:** `pip install pandas numpy matplotlib seaborn`

**3. Run the Notebook:**
  - Open Flipkart_Customer_Support_Analysis.ipynb in Jupyter Notebook.
  - Execute cells sequentially to load data, perform EDA, and visualize results.

**4. Explore Results:** Review visualizations and recommendations in the notebook. <br><br>

---
### Recommendations
**1. Improve CSAT Scores:**
  - **Action:** Deploy AI chatbots for quick responses, prioritize refunds/cancellations, and train evening shift agents.
  - **Impact:** Higher retention and better brand reputation.
  
**2. Reduce Response Time**
  - **Action:** Use AI ticket routing, increase staffing during peak hours, and offer self-service options.
  - **Impact:** Enhanced customer experience and lower costs.

**3. Enhance Issue Handling**
  - **Action:** Form dedicated refund teams, automate approvals, and provide proactive updates.
  - **Impact:** Fewer escalations and reduced agent workload. <br><br>

---
### Future Enhancements
- **Predictive Analytics:** Forecast peak query times and potential issues.
- **Sentiment Analysis:** Analyze Customer Remarks for deeper insights.
- **Channel Optimization:** Compare channel-specific performance (chat vs. email vs. phone).
- **Real-Time Dashboard:** Build an interactive tool for live support monitoring. <br><br>

---
### Conclusion
This EDA highlights critical areas for Flipkart to improve customer support—faster resolutions, targeted training, and automation. Implementing these data-driven strategies will elevate satisfaction, reduce costs, and strengthen Flipkart’s position in the e-commerce market. 🚀
