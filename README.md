# Student-Engagement-and-Performance-Evaluation-at-Tech-Studio-Academy-2024-2025-
This report presents a comprehensive analysis of student engagement and academic performance at Tech Studio Academy for the academic years 2024 and 2025
## INTRODUCTION ##
<img width="1302" height="737" alt="Screenshot 2025-11-06 234119" src="https://github.com/user-attachments/assets/650dcd68-e49d-43f1-aa34-63a57704ed14" />

This report presents a comprehensive analysis of student engagement and academic performance at Tech Studio Academy for the academic years 2024 and 2025. The primary goal is to leverage data-driven insights to understand the factors influencing student success, identify areas of strength and weakness across different programs and demographics, and provide actionable recommendations to enhance the overall educational experience, improve completion rates, and foster higher levels of student achievement.


# Business Understanding


## Nature of the Business 

Tech Studio Academy is an educational institution specializing in accelerated, practical technology training programs. It offers courses such as Data Analytics, Data Science, Full Stack Development, and UI/UX Design, delivered through both onsite and online learning modes to a diverse student population across major Nigerian cities.

The analysis of student engagement and performance data directly supports the following core business goals

* Improve Student Retention and Completion Rates: To ensure students who enroll complete their programs, maximizing educational outcomes and securing future enrollments through positive results and reputation
* Optimize Resource Allocation: To strategically allocate instructors, mentorship resources, and support services across different programs, learning modes, and geographic locations for maximum impact and operational efficiency.
* Maintain and Enhance Educational Quality: To uphold a high standard of educational delivery by identifying the most effective programs and teaching methodologies, and by pinpointing where curriculum or support structures need strengthening.
* Understand Drivers of Student Success: To move beyond anecdotal evidence and use data to conclusively identify the key factors (e.g., attendance, participation, mentorship) that lead to high student performance, enabling the academy to replicate these successes systematically.
* · Inform Strategic Planning: To provide a data-driven foundation for making strategic decisions regarding the expansion of online offerings, the introduction of new programs, and the development of targeted student support initiatives.

  ##  Data Understanding
  The dataset, student_engagement_performance.csv, contains 20 records of students from 2024 and 2025. It includes the following key fields:
 * Identifiers: Student_ID, Name.
 * Demographics: Gender, Age, City
 * · Academic Info: Program, Learning_Mode (Onsite/Online), Completion_Status, Year, Final_Grade (%)
 * Engagement Metrics: Attendance_Rate (%), Participation_Score (out of 10), Internship_Sessions (count), Satisfaction_Score (out of 10)

  The data is structured and mostly numerical or categorical, making it suitable for the planned analysis. The primary metrics for evaluation are the Final Grade (%) and Completion Status.
  ##  Exploratory Data Analytics (EDA)
  Steps and Findings
  1. Overall Performance: The student body has a strong overall performance with an average final grade of 80.1% and a completion rate of 78.3%.
2. Program Analysis: The UI/UX Design program showed the highest average engagement level (85.7%), while Full Stack Dev had the lowest (76.8%).
3. Learning Mode Comparison: A significant gap was identified. On-site learners outperformed online learners in both average final grade (84.1% vs. 76.1%) and average engagement (85.0% vs. 73.4%).
4. Geographical Analysis: Completion rates varied by city. Abuja has the highest completion rate at 100% (4 out of 4 students completed). Ibadan has a 50% completion rate (1 completed, 1 dropped), and Port Harcourt has a 67% completion rate (2 completed, 1 dropped). Lagos has a completion rate of 71.4%.
5. Correlation Analysis: · A strong positive correlation was observed between a student's Engagement_Level and their Final_Grade (%).
   · A moderate positive correlation was found between the number of Internship_Sessions a student attended and their Satisfaction_Score.
## Data Visualization
A Power BI report was developed with the following interactive visuals:

* KPI Tiles: Displaying Avg Engagement (79.2%), Avg Final Grade (80.1%), Completion Rate (78.3%), and Avg Satisfaction (7.8/10).
  
1. Donut Chart (Engagement by Program): Clearly shows UI/UX Design at the top, allowing for easy program comparison.
2. Bar Chart (Onsite vs. Online): Directly visualizes the performance and engagement gap between the two learning modes.
3. Bar Chart (Completion Rate by City): Highlights geographical disparities, with Abuja as the top performer and Ibadan the lowest.
4. Line and Stacked Column Chart (Engagement vs. Final Grade): Illustrates the strong positive correlation with a trend line.
5. Scatter chart (Internship Sessions vs. Satisfaction): Shows the positive relationship between mentorship and student satisfaction.
6. Slicers: Interactive filters for Year, Program, Learning_Mode, and City allow users to drill down into specific cohorts.
## Analysis and Key Insights
- Engagement is the Key Driver of Success: The strongest insight is the direct link between engagement and final grades. Improving engagement is the most effective lever for improving academic outcomes
- The Online Learning Gap is a Critical Challenge: The significant underperformance of online students across all engagement and performance metrics indicates a systemic issue that needs addressing to ensure the quality and scalability of online offerings
- Mentorship Directly Impacts Student Satisfaction: Internship/mentorship sessions are not just for skill development; they are a crucial tool for boosting student morale and overall satisfaction with the program.
- Localized Support is Needed: The low completion rates in Ibadan (50%) and Port Harcourt (67%), alongside Lagos, suggest that student challenges may be location-specific. Strategies must be tailored to address the specific issues faced by students in these locations.

## Summary of Findings
In summary, Tech Studio Academy maintains a generally healthy and successful learning environment. However, the analysis reveals clear opportunities for improvement. The academy excels in UI/UX Design and onsite programs, but faces challenges with student engagement in online courses and the Full Stack Dev program. Furthermore, student outcomes are inconsistent across geographical locations, with Abuja being a standout success and Ibadan showing a significant need for support. The core finding is that by strategically boosting student engagement—particularly through mentorship and tailored support—the academy can significantly improve completion rates and final grades.

## Recommendations
1. Enhance the Online Learning Experience: Implement mandatory, short, synchronous "checkpoint" workshops for online students to foster a sense of community and accountability, mirroring the engagement benefits of onsite learning.
2. Implement a Proactive Mentorship Program: Identify students with low satisfaction scores (<7) and automatically offer them one additional mentorship session per week to address issues early.
3. Launch Targeted Support in Key Cities: Initiate support pilots for Ibadan, Port Harcourt, and Lagos. Strategies could include weekend office hours, facilitated local study groups, and connecting students with alumni mentors from their city to address location-specific challenges.
4. Gamify Participation and Engagement: Introduce a digital badge and reward system (e.g., for high participation in discussions) to intrinsically and extrinsically motivate students, thereby directly increasing the Participation_Score component of engagement.
## Conclusion
The data provides a clear roadmap for Tech Studio Academy to enhance its educational offerings. By focusing on the critical levers of engagement, mentorship, and localized support, the academy can bridge the performance gap between its learning modes, strengthen its weaker programs, and ensure that all students, regardless of location or delivery mode, have the opportunity to succeed. Adopting these data-informed strategies will solidify Tech Studio Academy's position as a leader in effective and inclusive tech education.

