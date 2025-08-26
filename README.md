# US Elections Tweets 2020 Data Analysis

## Project Description  
This project analyzes **1.7M+ tweets** from the 2020 US Elections to uncover insights into political discourse around Trump and Biden.  
Through preprocessing, exploratory data analysis, clustering, and frequent pattern mining, the project reveals sentiment trends, geographic patterns, and social dynamics of online political engagement.  

## Features  
- 🧹 **Preprocessing & Cleaning**: Handled missing values, removed noise, normalized user/location data  
- 📊 **Exploratory Data Analysis (EDA)**: Candidate-wise, sentiment-wise, location-based, and hashtag analysis  
- 🌍 **Geographic Trends**: Visualized tweets across countries, states, and cities  
- 💬 **Sentiment Analysis**: Classified tweets as positive, negative, or neutral  
- 🔎 **Cluster Analysis**: Applied K-means and DBSCAN to group tweets by content, source, and engagement  
- 🔗 **Frequent Pattern Mining**: Used FP-growth & Apriori to extract frequent hashtags, sources, and associations  

## Technologies Used 
- **Languages**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, NLTK, WordCloud, mlxtend (Apriori/FP-growth)  
- **Algorithms**: Logistic Regression (baseline), K-means, DBSCAN, Apriori, FP-growth  
- **Data Source**: Twitter API — US Election Tweets 2020 dataset (1,747,805 tweets)  
