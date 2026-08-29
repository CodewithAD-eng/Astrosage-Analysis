# Astrosage Operational Analysis
An Excel-based analysis of call center and consultation operations for AstroSage, India's leading online astrology platform, covering call volume, agent(guru) performance, customer satisfaction, and revenue trends.

# Problem Statement
* You are tasked with optimizing the call center operations for AstroSage, which has received a 1 crore investment. The goal is to determine how to allocate this investment to maximize operational efficiency, customer satisfaction, and profitability. This project will involve analyzing historical call data, performance metrics, and market trends to make informed decisions.

# Objectives
* Analyze sales performance to identify trends across time (daily, weekly, monthly).
* Evaluate astrologers' performance and engagement.
* Analyzing call center performance using real time data.
* Building an excel dashboard to visualize trends, agent's matrix and call patterns.

# Dataset
* Includes customer details, astrologer details, consultation type, duration, and ratings.

# Key Findings
* Call Volume
8,365 total calls recorded over 34 working days — averaging 246 calls/day
* Agent Base
131 unique agents (gurus) handling calls, averaging 1.87 calls per agent per day — indicating underutilization
* Customer Satisfaction
Of 151 gurus, only 86 (57%) achieved an average rating above 3, while 63 (47%) scored below 3 — pointing to inconsistent service quality
Overall average rating: 2.93 | Highest individual rating: 7.5
* Call & Chat Outcomes
Only 41.26% of calls and 28.36% of chats were completed successfully
* Revenue
₹2,13,987.31 generated during the observed period
Product-wise split: Call 69.63%, Chat 30.36%, remainder from Complementary/Public Live Call

# Dashboard
* The interactive dashboard ("AstroSage Analysis") includes:
* KPI cards: Total Agents, Total Revenue, Average Rating, Total Calls, Highest Rating
* Product-wise revenue, website distribution, chat distribution, call distribution (pie charts)
* Rating-wise guru distribution and user-wise ratings (bar charts)
* Top 10 highest-rated gurus
* Hourly call distribution and daily call volume trends
* Slicers for website, consultation type, month, and year for interactive filtering

# Hiring vs Training vs Technology
To answer the problem statement, guru ratings were split into two groups — gurus rated ≥ 3 and gurus rated < 3 — and compared against workload and completion-rate data.
* Hiring — not recommended right now
  Each agent handles only ~1.87 calls/day on average, showing there is already more than sufficient manpower
  Hiring adds recurring costs without solving the underlying quality gap
* Training — highly recommended
  About 41% of gurus are rated below average, showing inconsistent service quality
  Training requires only moderate investment and directly improves guru performance
* Technology — recommended for system-level issues
  Only 41.26% of calls and 28.36% of chats were completed successfully, with failures mainly due to system inefficiencies rather than agent performance
  Technology upgrades require higher initial investment but improve efficiency and the overall customer experience

# Recommendation
Prioritize training for immediate, cost-effective quality improvement, paired with a technology upgrade to fix the system inefficiencies driving low call/chat completion rates. Hiring is not justified given current agent underutilization.


