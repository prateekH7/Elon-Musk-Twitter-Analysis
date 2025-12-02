Decoding Digital Influence: Analyzing Elon Musk’s Twitter Communication

Sentiment Analysis • NLP • Social Media Engagement • R

This project analyzes Elon Musk’s tweets to understand how sentiment, emojis, hashtags, content type, and industry language influence public engagement. Using R’s text mining ecosystem (tidytext, textstem, ggplot2), this study investigates tweet sentiment, emotion frequencies, engagement trends, crisis communication, and virality patterns.

📌 Key Analyses

✔ Sentiment scoring using NRC, Bing, Afinn lexicons
✔ Emoji extraction + emotional categorization
✔ Document-Term Matrix (DTM) construction
✔ Lemmatization + stop-word filtering
✔ Crisis vs non-crisis tweet comparison
✔ Engagement analysis across industries (Tech, Retail, Finance)
✔ Impact of hashtags & multimedia on engagement
✔ Virality comparison: Influencers vs Regular Users
✔ Word cloud, top-word frequencies, sentiment density plots

📊 Core Findings

Positive tone, anticipation, and trust drive the highest engagement

Emojis boost engagement, especially in positive or humorous tweets

Hashtags significantly increase retweets and visibility

Tesla and SpaceX-related tweets outperform all other topics

Crisis-related tweets generate nearly 2× more engagement

Multimedia content increases likes and retweets across all categories

Visualizations referenced from the paper include bar plots (pg. 17–45) and word clouds.

🧠 Technologies Used

R

tidytext

textstem

ggplot2

dplyr

tm

NLP techniques

Visualization libraries

📂 Project Structure
Elon-Musk-Twitter-Analysis/
│── data/
│── code/
│── figures/
│── report/
│    └── Harlikar_Final_Research_Paper.pdf
│── README.md
│── sentiment_analysis.R

🚀 How to Run

Install packages:

install.packages(c("tidytext", "textstem", "ggplot2", "dplyr", "tm"))


Run sentiment_analysis.R

View the generated plots in the figures/ directory

📑 Full Paper

See:
Harlikar_Final_Research_Papers.pdf
(Uploaded in report/)

👤 Author

Pratik Harlikar
Master of Data Analytics — NMSU
NLP • Machine Learning • Data Visualization
