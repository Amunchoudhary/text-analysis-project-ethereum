Ethereum News Text Analysis

This project performs text analysis on Ethereum-related news headlines/articles using Python, NLP techniques, and machine learning models.

🚀 Features

Data Preprocessing

Handles missing values

Tokenization

Lowercasing

Removes special characters

Stopwords removal

Sentiment Analysis

Uses TextBlob to calculate sentiment polarity

Categorizes news as Positive, Negative, or Neutral

Results stored in Excel for further analysis

Visualization

Pie Chart of sentiment distribution

Bar Charts for top words in each topic

Word Clouds for topic representation

Topic Modeling

Applies TF-IDF Vectorization

Uses NMF (Non-Negative Matrix Factorization) for topic extraction

Displays top words per topic

N-Gram Analysis

Extracts and displays most common Bigrams and Trigrams

🛠️ Technologies Used

Python

Pandas, NumPy for data manipulation

NLTK for text preprocessing (tokenization, stopwords, n-grams)

TextBlob for sentiment analysis

Scikit-learn for TF-IDF and NMF topic modeling

Matplotlib, WordCloud for visualization

📂 Project Workflow

Load raw Ethereum news data from Excel

Preprocess text (cleaning + tokenization)

Perform sentiment analysis

Save processed results into processed_ethe_data.xlsx

Visualize sentiment categories with a pie chart

Apply NMF for topic modeling

Generate bar charts and word clouds for topics

Extract and display common bigrams & trigrams

📊 Example Outputs

Pie chart of sentiment distribution (Positive / Negative / Neutral)

Word clouds showing topic keywords

Top 20 most frequent bigrams and trigrams

📦 Installation

Clone this repository and install dependencies:

git clone https://github.com/your-username/ethereum-news-analysis.git
cd ethereum-news-analysis
pip install -r requirements.txt


Required libraries include:

pandas
nltk
textblob
matplotlib
scikit-learn
wordcloud

▶️ Usage

Place your Ethereum news dataset in the project folder.

Update the file path in the code (project gba 2 ethereum.xlsx).

Run the script:

python analysis.py


Processed results will be saved to:

processed_ethe_data.xlsx

Visualizations will be displayed as charts/word clouds.

📌 Future Improvements

Integrate live Ethereum news API for real-time analysis

Deploy as a web dashboard (Streamlit/Dash)

Add deep learning sentiment analysis models (BERT, RoBERTa)

📜 License

This project is licensed under the MIT License.
