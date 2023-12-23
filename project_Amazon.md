## Amazon Risk Forecast and Analysis

(In consideration of the company's confidentiality policies, I will refrain from sharing any visual representations of the final product.)

### Project Overview

For my intern project at Amazon, I delivered a risk trend analysis tool with ML-powered forecasting for audit managers and data analysts. The director of Internal Audit was personally invested in my project because it played a role in the department’s big direction toward data-driven risk insights. 

### Process

Throughout this internship, I had the privilege to meet with more than fifteen auditors and data scientists/engineers to learn about their needs and suggestions. Just a few years ago, the auditors planned for audits manually because they did not have the tools to extract insights from data. It would help their planning process if I made a tool that quickly identified the top risk themes in a business unit in an explainable way.

To draw out insights from a treasure trove of textual data, I implemented an anomaly detector, a top risk theme identifier, and an XGBoost forecast model. I also designed an interactive AWS QuickSight dashboard showing big-picture trends and deep-diving insights. 

To insist on the highest standards, I compared many state-of-the-art forecasting models like DeepAR, XGBoost, LightGBM, and Meta’s Prophet, and XGBoost outperformed all other choices in speed and reliability. I fine-tuned the model using a percentage-based error metric, which is scale-independent and resistant to outliers. I also streamlined my code to update easily with new data and adjust quickly to new changes.

Throughout this process, I frequently asked for feedback from my manager and the auditors, so I knew I was still on track to address their needs. One auditor said he loved what I made, but he wished there was a way to investigate a particular data point. In response to the auditor’s feedback, I improved my dashboard by adding the functionality to click on a data point to navigate to another tab that showed more in-depth analysis. I also designed a new but intuitive metric to show how a department compares horizontally to another department in different risk categories. To further improve the dashboard user experience, I found creative ways to fully utilize AWS QuickSight’s capabilities, such as using customized narratives, navigation actions, parameter-based calculated fields, and cascading filters. Thanks to my customers’ feedback, I produced a product that I can be proud of because it actually satisfied the business needs. 

### Impact

- Replaced parts of manual audit planning with data-driven insights
- Provided material for audit managers to start conversations with stakeholders and points of contact
- Filled in missing functionalities from existing tools:
  - Identified unusual/anomaly activity periods for the auditors to deep dive
  - Compare trends of a single business unit to its vertical as a benchmark
  - Identified correlations between risk event trends and other metrics for faster root cause analysis
  - Visualized 3-month projections for informed risk tracking and decision-making





