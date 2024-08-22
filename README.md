# BELLABEAT_CASE_STUDY_GOOGLE_DATA_ANALYTICS

# Bellabeat Overview:

Bellabeat is a high-tech manufacturer of health-focused products for women. The company was founded in 2013 by Urška Sršen and Sando Mur. Bellabeat's product lineup includes the Bellabeat app, Leaf, Time, Spring, and the Bellabeat Membership program. The company is positioned to become a larger player in the global smart device industry, with a strong focus on women’s health and wellness. The founders believe that analyzing smart device fitness data can help unlock new growth opportunities.

# Project Context:

To achieve this, I decided to analyze data from FitBit Fitness Trackers. My goal was to focus on the Bellabeat Membership program, leveraging the FitBit data to understand how users interact with their fitness devices and, ultimately, to extract insights that could inform Bellabeat’s strategy moving forward. I followed the six steps of the data analysis process: ask, prepare, process, analyze, share, and act, to ensure a thorough approach.

# ASK

Key Stakeholders:

Urška Sršen: Cofounder and Chief Creative Officer at Bellabeat.

Sando Mur: Cofounder and a driving force within the Bellabeat executive team.

Bellabeat’s Marketing Analytics Team: The team responsible for collecting, analyzing, and reporting data to steer the company’s marketing efforts.

Customers: The end-users who purchase Bellabeat’s products and services.

# Business Task:

The task I set out to accomplish was to analyze FitBit Fitness Tracker data from 33 eligible FitBit users. By doing so, I aimed to gather actionable insights that could help Bellabeat identify new growth opportunities, particularly within their Membership program, which offers personalized wellness guidance on various aspects of health and lifestyle.

# PREPARE

Data Source:

The data I worked with comes from a free-to-use FitBit Fitness tracker dataset provided by Mobius. It includes personal fitness tracker data from 33 FitBit users who have given their consent for their data to be used.
Data Structure:

The dataset contains 18 CSV files, but for my analysis, I zeroed in on the most relevant ones:
dailyActivity_merged.csv: Provides metrics like total steps, active minutes, and calories burned.
hourlyCalories_merged.csv: Contains data on hourly calories burned.
hourlySteps_merged.csv: Tracks hourly steps taken.
sleepDay_merged.csv: Contains data on sleep patterns and duration.

# Data Credibility:

Reliability: With a sample size of 33 users, I felt confident that the insights I would derive could be generalized to a broader audience.
Recency: The data is still relevant and current, being less than 10 years old.
Relevance: The metrics within the dataset align well with Bellabeat’s product offerings, making the insights applicable to their business strategy.
Quality: Even though the data is third-party, it is credible, sourced from a reliable provider, and organized in a way that supports thorough analysis.

# Limitations:

The dataset represents a relatively small sample size, which may not capture the full diversity of Bellabeat’s user base.
It also lacks demographic information, which could have added depth to the analysis by allowing for segmentation of insights.

# PROCESS

Data Cleaning:

I started by cleaning the data to ensure its integrity. This involved removing duplicate records, addressing any missing values, and standardizing data formats—especially for date and time entries.

# Data Transformation:

To make the analysis more robust, I created new features, such as daily averages and correlations between key metrics (e.g., steps taken and calories burned).
I also merged datasets where necessary to get a more comprehensive view of user behavior.

# ANALYZE

Exploratory Data Analysis (EDA):

Daily Activity: My analysis focused on understanding users’ overall activity levels by looking at total steps, active minutes, and calories burned.
Hourly Trends: I dug into the hourly datasets to identify when users were most active and how this correlated with calorie expenditure.
Sleep Patterns: I explored the sleep data to understand how sleep duration and quality affected users’ daily activity levels and overall wellness.

# Key Insights:

Correlation Between Activity and Calories: There was a strong positive correlation between the number of steps taken and calories burned. This reinforced the idea that more active users are burning more calories—a key insight for wellness recommendations.

Peak Activity Hours: I identified specific times of day when users were most active. This insight could be valuable for timing personalized recommendations or wellness challenges.

Impact of Sleep on Activity: Users who slept better and longer tended to be more active during the day. This suggests that promoting good sleep hygiene could be a significant factor in enhancing overall wellness.

# SHARE

Data Visualization:

To present my findings, I created visualizations including bar charts, line graphs, and heatmaps, which effectively conveyed the key insights.

Reporting:

I compiled a detailed report summarizing the insights and provided actionable recommendations that Bellabeat could use to refine their Membership program and other product offerings.

Presentation:

The findings were presented to Bellabeat’s executive team, emphasizing how these insights could be leveraged to enhance the Membership program and drive engagement.

# ACT

Product Enhancements:

Based on my analysis, I recommended that Bellabeat refine its Membership program by aligning its features with users’ peak activity times and sleep patterns. This could include personalized wellness challenges and targeted recommendations to boost engagement.
Marketing Strategy:

I suggested that Bellabeat develop targeted marketing campaigns highlighting the personalized wellness guidance available through the Membership program. Leveraging data-driven insights, these campaigns could attract new members and retain existing ones.
Customer Engagement:

Finally, I recommended offering personalized recommendations based on individual activity and sleep data, which could enhance user satisfaction and encourage regular use of Bellabeat products.
