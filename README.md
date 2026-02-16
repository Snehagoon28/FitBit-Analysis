# FitBit-Analysis

Project Details
Author: Sneha Shekhar Goon

Project Summary
Analysis of FitBit user data from 18 sources to identify trends and provide marketing insights. Data includes daily activity, calories, steps, sleep patterns, and heart rate collected via Amazon Mechanical Turk survey.
Tools & Technology
Language: Python
Libraries: pandas, numpy, seaborn, matplotlib, plotly, scipy
Environment: Jupyter Notebook
Data Period: April-May 2016
Methodology

Ask: Define business objectives and key questions
Prepare: Clean, merge, and validate 5 datasets (daily activity, hourly calories/steps/intensities, sleep data)
Process: Remove duplicates, format data types, create merged datasets
Analyze: Statistical analysis, visualizations, correlation studies
Act: Generate insights and recommendations

Key Findings: 

Activity Patterns
- Average daily: 2,307 calories burned, 7,652 steps
- Time allocation: 81% sedentary (16.5 hrs), 3.2 hrs lightly active, 21 min very active
- Distance: 3.35 km in lightly active level (highest)
- Peak activity: 5-7 PM daily

Weekly Trends
- Calories: Highest Saturday (2,365), lowest Thursday (2,204)
- Steps: Highest Tuesday (8,125), lowest Sunday (6,993)

Sleep Analysis
- Average: 419.5 minutes (~7 hours) consistently
- 44.3% have inadequate sleep (<7 hours)
- Peak sleep: Sundays (7.5 hrs), lowest Thursdays (6.7 hrs)

Correlations
- Strong relationship: Steps and calories (r=0.6, 0.08 calories per step)
- 5+ strong correlations identified (r>0.6) between various metrics

Major Concerns
- Excessive sedentary behavior (81% of day)
- Nearly half of users have insufficient sleep
- Minimal very active exercise time

Visualizations Created
Histograms: Activity level distributions, sleep hour distributions
Pie Charts: Time allocation across activity levels, sleep adequacy proportions
Bar Charts: Calories by day of week, distance by activity level
Box Plots: Step count distributions by day of week
Line Charts: Hourly calorie and step patterns
Scatter Plots: Steps vs calories correlation
Heatmap: Comprehensive correlation matrix of all variables

Marketing & Business Recommendations

1. Combat Sedentary Behavior
Implement hourly movement reminders
Create "break up your sitting" challenges
Develop desk exercise notifications
Gamify standing/movement goals

2. Optimize Peak Activity Time (5-7 PM)
Schedule push notifications during this window
Create post-work workout challenges
Promote evening walking groups/communities
Target ads for this time slot

3. Sleep Improvement Initiative
Develop comprehensive sleep tracking features
Create bedtime routine recommendations
Target 44.3% inadequate sleepers with sleep programs
Implement wind-down reminders

4. Personalized Goal Setting
Use 7,652 steps as baseline for new users
Leverage steps-calories correlation (0.08 cal/step) for weight management
Create adaptive goals based on activity patterns
Segment users by activity level

5. Light Activity Recognition
Market to non-athletes and wellness-focused users
Celebrate everyday activities (walking, housework, gardening)
Emphasize lifestyle tracking over athletic performance
Create age-diverse marketing campaigns

Business Impact & Applications

Immediate Applications:
Product Development: Feature prioritization based on actual usage patterns
Marketing Strategy: Time-targeted campaigns, audience segmentation
User Engagement: Personalized notifications and challenges
Health Initiatives: Sleep and sedentary behavior interventions

Long-Term Strategy:
Predictive Analytics: Use correlations for automated goal adjustment
User Retention: Address health concerns before users abandon device
Market Positioning: Focus on everyday wellness vs athletic performance
Community Building: Leverage consistent activity patterns for social features


Conclusions
This analysis reveals that FitBit users are primarily everyday people tracking lifestyle activities rather than athletes monitoring training. The significant sedentary behavior (81% of day) and sleep issues (44.3% inadequate) present both challenges and opportunities. The strong correlations between metrics enable predictive features, while the consistent temporal patterns (5-7 PM peak, Sunday rest) provide clear targets for engagement strategies. The data supports positioning FitBit as a wellness device for general populations rather than a fitness tool for athletes.
