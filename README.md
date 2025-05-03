# Admission-Process-Analysis
This project analyzes the university’s admissions funnel using applicant data across several touchpoints — from application to enrollment. The goal is to uncover trends, identify process bottlenecks, and provide actionable insights to improve conversion rates, outreach strategies, and overall admissions efficiency.

📊 Objective
Understand the applicant journey and identify drop-offs in the admissions funnel.

Explore demographic trends and applicant performance across programs.

Evaluate communication effectiveness and provide strategic recommendations for optimization.

🧹 1. Data Preparation
Cleaned and transformed data in Power Query:

Handled missing/null values.

Standardized communication channels.

Corrected and assigned appropriate data types.

Established relationships across multiple datasets using ApplicationID:

Demographics

Interviews

Aptitude Scores

Communication Logs

📈 2. Data Analysis & Key Insights
🔄 Admissions Funnel
Tracked progression: Applications → Communicated → Interviewed → Accepted.

Calculated conversion rates to detect drop-off stages.

🌍 Demographic Trends
Identified top cities by acceptance volume.

Binned age groups to reveal engagement trends.

Gender distribution and conversion rate visualized.

🧠 Applicant Performance
Analyzed average aptitude scores (Quantitative, Verbal, Logical) by program.

Evaluated interview scores by department using DAX.

📞 Communication Efficiency
Calculated average response time per channel.

Measured conversion rate by communication channel to assess outreach effectiveness.

📊 3. Visualizations
Funnel Chart: Admissions stages from Application to Acceptance.

Bar Charts: Top Cities, Age Group Distribution.

Line Chart: Conversion Rate by Communication Channel.

Area Chart: Interview Score Trends by Program.

Pie Chart: Enrollment by Gender.

Performance Dashboard: Response Time vs Conversion Rate by Channel.

🧮 4. Advanced DAX Calculations
Average Interview Score by Department

Conversion Rate = Accepted / Applications

✅ 5. Recommendations
1. Optimize Communication Channels
Phone calls have the highest conversion (26.54%).

Allocate more resources to call-based outreach and automate follow-ups via WhatsApp/Email.

2. Focus on High-Yield Demographics
Prioritize top cities: New Michael, Johnfort, North John.

Target age group 21–30 in outreach campaigns.

Leverage gender-balanced acceptance to maintain inclusive strategies.

3. Address Enrollment Drop-Off
75% drop-off post-interview stage.

Recommend follow-ups, scholarship discussions, and orientation sessions to increase enrollment.

4. Department-Level Performance Insights
Programs like Engineering, CS, and Business show strong interview scores.

Recommend improving interview guidance for Law and Arts applicants.

5. Improve Communication Efficiency
Track and reduce response delays.

Align follow-up timings with highest-performing channels.

📁 Project Files
.pbix file with all visuals, filters, and calculations

README.md for documentation

Power Query transformations within Power BI

🚀 Tools & Technologies
Power BI: Data visualization & reporting

Power Query: Data cleaning & transformation

DAX: Advanced calculations and KPIs

📌 Conclusion
This project demonstrates how a structured data analysis approach using Power BI can yield actionable insights into the admissions pipeline. It highlights the importance of demographic targeting, channel performance, and personalized communication in optimizing university admissions.
