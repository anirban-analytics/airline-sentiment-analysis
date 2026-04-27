✈️ Airline Social Media Sentiment Analysis & Engagement Intelligence








📌 Overview

This project analyzes large-scale Twitter data to uncover customer sentiment, engagement patterns, and operational pain points across major U.S. airlines.

By combining Natural Language Processing (NLP) with interactive data visualization, the project transforms unstructured social media data into actionable business intelligence.

⚡ Designed to simulate a real-world analytics use case where companies monitor brand perception and customer experience in real time.

🎯 Business Objective

Airlines receive thousands of customer interactions daily via social media, but:

Feedback is unstructured and difficult to analyze
Critical issues are buried in noisy text data
Decision-makers lack real-time visibility into customer sentiment
✅ Solution

This project builds an end-to-end pipeline to:

Structure and clean raw tweet data
Perform sentiment analysis
Identify key complaint drivers
Visualize insights through an interactive dashboard
📊 Key Results & Insights
~60% of tweets are negative, indicating widespread dissatisfaction
Customer Service Issues (~2,900 tweets) are the leading complaint category
Flight Delays (~1,600+) are the second major driver of negative sentiment
A sharp spike in negative sentiment observed around Feb 22, suggesting potential operational disruption
United Airlines shows the highest negative sentiment volume
Engagement analysis reveals uneven customer interaction across airlines

👉 These insights highlight service quality and operational reliability as primary improvement areas.

🧠 Methodology
1. Data Collection
Twitter US Airline Sentiment dataset (~14,000+ tweets)
2. Data Preprocessing (NLP Pipeline)
Text normalization (lowercasing)
Removal of URLs, mentions, hashtags, punctuation
Tokenization
Stopword removal
Lemmatization
3. Exploratory Data Analysis (EDA)
Sentiment distribution analysis
Airline-wise sentiment comparison
Complaint category breakdown
Time-series trend analysis
Engagement (retweet) analysis
4. Visualization
Built an interactive Tableau dashboard for stakeholder-friendly insights
📈 Dashboard
🔗 Live Dashboard

👉 (https://public.tableau.com/app/profile/anirban.tarafdar/viz/SocialMediaAnalytics_17772726801180/AirlineSocialMediaSentimentDashboard?publish=yes)

📌 Key Views
Overall Sentiment Distribution
Airline-wise Sentiment Comparison
Top Complaint Categories
Sentiment Trend Over Time
Airline Engagement Performance
🛠️ Tech Stack
Programming: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn
NLP: Text preprocessing techniques
Visualization: Tableau
Environment: Jupyter Notebook
Version Control: Git & GitHub
📂 Project Structure
airline-sentiment-analysis/
│
├── data/              # Raw & processed datasets
├── notebooks/         # Jupyter notebooks (EDA + NLP)
├── dashboard/         # Tableau workbook (.twbx)
├── images/            # Dashboard screenshots
└── README.md
💼 Business Impact

This project demonstrates how organizations can:

📉 Detect and reduce customer dissatisfaction
⚡ Identify operational inefficiencies (delays, service gaps)
📊 Monitor brand sentiment in near real-time
🎯 Prioritize improvements based on data-driven insights
🔮 Future Enhancements
Build a machine learning model for automated sentiment prediction
Deploy as a real-time analytics dashboard (Streamlit / web app)
Integrate live Twitter API streaming
Perform aspect-based sentiment analysis
🚀 How to Run
git clone https://github.com/anirban-analytics/airline-sentiment-analysis.git
cd airline-sentiment-analysis
Open notebooks in Jupyter
Explore dataset in /data
Open Tableau dashboard from /dashboard
👤 Author

Anirban Tarafdar
Aspiring Data Analyst | Data Visualization | Business Intelligence

⭐ Acknowledgment

Dataset: Twitter US Airline Sentiment Dataset (2015)

🌟 Support

If you found this project useful:

⭐ Star the repository
🍴 Fork it
🔗 Share it