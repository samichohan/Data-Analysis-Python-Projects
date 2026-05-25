📌 Project Overview


This project performs Sentiment Analysis on the IMDB Movie Reviews Dataset from Kaggle. The goal is to classify movie reviews as Positive or Negative using Natural Language Processing (NLP) techniques including text cleaning, preprocessing, and exploratory data analysis.

📊 Dataset Information


FeatureDetailSourceKaggle - IMDB DatasetRows50,000Columns2ClassesPositive / Negative

Key Columns:



ColumnDescriptionreviewMovie review textsentimentPositive (1) or Negative (0)


🧹 Data Cleaning

✅ Found and removed 418 duplicate records


✅ Final dataset: 49,582 rows

✅ No missing values found
✅ Label Encoding applied on sentiment column (positive=1, negative=0)




📈 EDA Insights
1️⃣ Sentiment Distribution

SentimentCountPositive (1)24,884Negative (0)24,698


Dataset is perfectly balanced — almost 50/50 split ✅



2️⃣ Review Length Analysis

New features created to analyze review length:

FeatureDescriptionnum_charactersTotal characters in each reviewnum_wordsTotal words in each reviewnum_sentencesTotal sentences in each 
review

3️⃣ Key Observations



Positive and negative reviews have similar length distribution

num_characters and num_words are highly correlated (0.99)

Sentiment has very low correlation with review length

Both positive and negative reviews tend to be long and detailed




🔤 Text Preprocessing Pipeline

StepWhat it does1. Remove ChatwordsConverts slang like LOL, IMHO to full words2. Remove HTML TagsRemoves <br/> and other HTML from 
reviews3. Remove URLsRemoves any web links4. Remove PunctuationsRemoves special characters5. LowercaseConverts all text to lowercase6. 

Remove StopwordsRemoves common words like "the", "is", "and"7. TokenizationSplits text into individual words



🛠️ Tech Stack


ToolPurposePythonCore programmingPandasData manipulationNumPyNumerical operationsNLTKNatural Language ProcessingMatplotlibData visualizationSeabornStatistical plotsScikit-learnLabel EncodingGoogle ColabDevelopment environment


📂 Project Structure

Sentiment-Analysis/


├── sentiment_analysis.ipynb    # Main notebook

├── IMDB Dataset.csv            # Dataset

└── README.md                   # Project documentation



🚀 How to Run
bash# Clone the repo
git clone https://github.com/samichohan/Data-Analysis-Projects.git

# Open notebook
jupyter notebook sentiment_analysis.ipynb
Or open directly in Google Colab.

👤 Author
Sami Chohan
