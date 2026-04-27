✈️ Airline Social Media Sentiment Analysis & Engagement Intelligence
> 📉 Airlines face significant customer dissatisfaction on social media.
> This project analyzes 14K+ tweets to identify key service failures and improve customer experience using data-driven insights.

## 📊 Live Dashboard  
🔗 [View Interactive Tableau Dashboard](https://public.tableau.com/app/profile/anirban.tarafdar/viz/SocialMediaAnalytics_17772726801180/AirlineSocialMediaSentimentDashboard?publish=yes)

## ⚡ At a Glance
- Dataset: 14,000+ airline tweets
- Tools: Python, NLP, Tableau
- Key Insight: 60% negative sentiment
- Output: Interactive dashboard + business insights

## 🆚 What Makes This Project Different
- End-to-end pipeline (data → insights → dashboard)
- Business-focused analysis (not just sentiment classification)
- Engagement + complaint analysis combined
- Interactive Tableau dashboard for stakeholders

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

📓 Notebook: [View Analysis](notebooks/Airline_Sentiment_Analysis_Advanced_Case_Study.ipynb)

📊 Key Results & Insights
- ~60% of tweets are negative, indicating systemic service issues
- Customer service (~2,900 tweets) is the primary complaint driver
- Delay-related complaints exceed 1,500 tweets
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