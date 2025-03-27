<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flipkart Customer Support Analysis</title>
    <style>
        body { font-family: Arial, sans-serif; line-height: 1.6; max-width: 800px; margin: 0 auto; padding: 20px; }
        h1 { text-align: center; color: #2874f0; }
        h2 { color: #333; border-bottom: 2px solid #2874f0; padding-bottom: 5px; }
        ul { list-style-type: none; padding-left: 0; }
        li { margin: 10px 0; }
        a { color: #2874f0; text-decoration: none; }
        a:hover { text-decoration: underline; }
        img { max-width: 100%; height: auto; }
        code { background: #f4f4f4; padding: 2px 5px; border-radius: 3px; }
        pre { background: #f4f4f4; padding: 10px; border-radius: 5px; overflow-x: auto; }
    </style>
</head>
<body>
    <h1>Flipkart Customer Support Analysis</h1>
    <img src="https://via.placeholder.com/1200x300.png?text=Flipkart+Customer+Support+Analysis" alt="Project Banner">
    <p><em>Exploratory Data Analysis (EDA) to Enhance Customer Satisfaction and Support Efficiency</em></p>

    <h2>Project Overview</h2>
    <p>In the competitive e-commerce landscape, exceptional customer service is vital for growth and loyalty. This project conducts an <strong>Exploratory Data Analysis (EDA)</strong> on Flipkart's customer support data, focusing on interactions, feedback, and satisfaction scores across multiple channels. The goal is to identify key factors influencing customer satisfaction, evaluate support team performance, and propose actionable strategies to optimize the customer experience.</p>
    <ul>
        <li><strong>Contributor:</strong> Rishabh Kumar</li>
        <li><strong>Type:</strong> Individual Project</li>
        <li><strong>GitHub Repository:</strong> <a href="https://github.com/Rishabh45/Flipkart_Customer_Support_Analysis_EDA" target="_blank">Flipkart_Customer_Support_Analysis_EDA</a></li>
    </ul>

    <h2>Problem Statement</h2>
    <p>Flipkart handles a high volume of customer queries daily, yet challenges like delayed responses, unresolved issues, and inconsistent satisfaction levels persist. This analysis aims to:</p>
    <ul>
        <li>Identify common complaint categories.</li>
        <li>Assess response times and their impact on CSAT scores.</li>
        <li>Evaluate agent performance and support channel effectiveness.</li>
        <li>Uncover patterns driving satisfaction levels.</li>
    </ul>

    <h2>Objectives</h2>
    <ol>
        <li><strong>Enhance CSAT Scores:</strong> Pinpoint factors lowering satisfaction and implement improvements.</li>
        <li><strong>Optimize Resolution Efficiency:</strong> Streamline workflows for faster issue resolution.</li>
        <li><strong>Boost Agent Performance:</strong> Improve training and workload management.</li>
        <li><strong>Reduce Support Costs:</strong> Automate repetitive tasks and optimize resources.</li>
        <li><strong>Enable Data-Driven Decisions:</strong> Leverage analytics for proactive support strategies.</li>
    </ol>

    <h2>Dataset Details</h2>
    <ul>
        <li><strong>Source:</strong> <a href="https://raw.githubusercontent.com/Rishabh45/Flipkart_Customer_Support_Analysis_EDA/refs/heads/main/Customer_support_data.csv" target="_blank">Customer_support_data.csv</a></li>
        <li><strong>Size:</strong> 85,907 rows, 20 columns</li>
        <li><strong>Key Columns:</strong>
            <ul>
                <li><code>CSAT Score</code>: Customer satisfaction rating (1-5)</li>
                <li><code>channel_name</code>: Support channel (e.g., chat, email, phone)</li>
                <li><code>category</code> & <code>Sub-category</code>: Issue type</li>
                <li><code>Issue_reported at</code> & <code>issue_responded</code>: Timestamps for response time analysis</li>
                <li><code>Agent_name</code>, <code>Agent Shift</code>: Agent performance metrics</li>
            </ul>
        </li>
        <li><strong>Missing Data:</strong> Notable in <code>Customer Remarks</code> (33%), <code>order_date_time</code> (80%), and <code>connected_handling_time</code> (99%).</li>
    </ul>

    <h2>Technologies Used</h2>
    <ul>
        <li><strong>Python:</strong> Core programming language</li>
        <li><strong>Libraries:</strong>
            <ul>
                <li><code>pandas</code> & <code>numpy</code>: Data manipulation</li>
                <li><code>matplotlib</code> & <code>seaborn</code>: Visualization</li>
                <li><code>IPython.display</code>: Enhanced output formatting</li>
            </ul>
        </li>
        <li><strong>Environment:</strong> Jupyter Notebook</li>
    </ul>

    <h2>Key Insights</h2>
    <ul>
        <li><strong>CSAT Distribution:</strong> Scores concentrate between 2-5, peaking at 3-4, with outliers below 0 and above 8.</li>
        <li><strong>Pain Points:</strong> Refunds, returns, and cancellations yield the lowest CSAT scores and highest complaint frequency.</li>
        <li><strong>Response Time Impact:</strong> Longer response and resolution times strongly correlate with lower CSAT scores.</li>
        <li><strong>Agent Performance:</strong> Evening shift agents show lower satisfaction ratings, indicating training or staffing gaps.</li>
    </ul>
    <img src="https://via.placeholder.com/600x400.png?text=CSAT+Score+Distribution+Plot" alt="CSAT Score Distribution">
    <p><em>CSAT scores peak at 3-4, with higher frequencies at the upper end.</em></p>

    <h2>Usage Instructions</h2>
    <ol>
        <li><strong>Clone the Repository:</strong>
            <pre><code>git clone https://github.com/Rishabh45/Flipkart_Customer_Support_Analysis_EDA.git</code></pre>
        </li>
        <li><strong>Install Dependencies:</strong>
            <pre><code>pip install pandas numpy matplotlib seaborn</code></pre>
        </li>
        <li><strong>Run the Notebook:</strong>
            <ul>
                <li>Open <code>Flipkart_Customer_Support_Analysis.ipynb</code> in Jupyter Notebook.</li>
                <li>Execute cells sequentially to load data, perform EDA, and visualize results.</li>
            </ul>
        </li>
        <li><strong>Explore Results:</strong> Review visualizations and recommendations in the notebook.</li>
    </ol>

    <h2>Recommendations</h2>
    <h3>1. Improve CSAT Scores</h3>
    <ul>
        <li><strong>Action:</strong> Deploy AI chatbots for quick responses, prioritize refunds/cancellations, and train evening shift agents.</li>
        <li><strong>Impact:</strong> Higher retention and better brand reputation.</li>
    </ul>
    <h3>2. Reduce Response Time</h3>
    <ul>
        <li><strong>Action:</strong> Use AI ticket routing, increase staffing during peak hours, and offer self-service options.</li>
        <li><strong>Impact:</strong> Enhanced customer experience and lower costs.</li>
    </ul>
    <h3>3. Enhance Issue Handling</h3>
    <ul>
        <li><strong>Action:</strong> Form dedicated refund teams, automate approvals, and provide proactive updates.</li>
        <li><strong>Impact:</strong> Fewer escalations and reduced agent workload.</li>
    </ul>

    <h2>Future Enhancements</h2>
    <ul>
        <li><strong>Predictive Analytics:</strong> Forecast peak query times and potential issues.</li>
        <li><strong>Sentiment Analysis:</strong> Analyze <code>Customer Remarks</code> for deeper insights.</li>
        <li><strong>Channel Optimization:</strong> Compare channel-specific performance (chat vs. email vs. phone).</li>
        <li><strong>Real-Time Dashboard:</strong> Build an interactive tool for live support monitoring.</li>
    </ul>

    <h2>Conclusion</h2>
    <p>This EDA highlights critical areas for Flipkart to improve customer support—faster resolutions, targeted training, and automation. Implementing these data-driven strategies will elevate satisfaction, reduce costs, and strengthen Flipkart’s position in the e-commerce market. 🚀</p>

    <hr>
    <p><em>Feel free to contribute or raise issues via the repository!</em></p>
</body>
</html>
