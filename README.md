<h1 align="center">🧹 Data Preprocessing & Cleaning</h1>

<p align="center">
  <strong>A complete pipeline for cleaning, normalizing, and preparing raw text data</strong><br>
  Applied on the IMDB Movie Review Dataset – ready for NLP & ML tasks.
</p>

<hr>

<h2>📌 Project Overview</h2>

<p>
This project demonstrates a <strong>comprehensive text preprocessing pipeline</strong> for Natural Language Processing (NLP).  
It cleans and transforms raw text into structured and meaningful data that can be used for Machine Learning models.
</p>

<ul>
  <li>🔡 <strong>Lowercasing</strong>: Normalize text</li>
  <li>🏷️ <strong>HTML & URL Removal</strong>: Strip unwanted tags/links</li>
  <li>✂️ <strong>Punctuation & Emoji Handling</strong>: Clean noisy characters</li>
  <li>💬 <strong>Chat Slang Conversion</strong>: Expand abbreviations like LOL → Laugh Out Loud</li>
  <li>🧠 <strong>Spell Correction</strong>: Fix common typos</li>
  <li>🛑 <strong>Stopwords Removal</strong>: Remove frequent but meaningless words</li>
  <li>🔎 <strong>Tokenization</strong>: Split into words/sentences</li>
  <li>🌱 <strong>Stemming & Lemmatization</strong>: Reduce words to root forms</li>
</ul>

<hr>

<h2>🚀 Features</h2>

<ul>
  <li>📂 Loads and preprocesses the <code>IMDB 50K Movie Reviews</code> dataset</li>
  <li>✂️ Handles HTML tags, URLs, emojis, punctuation, and abbreviations</li>
  <li>🧹 Provides functions for <strong>stopword removal, spell correction, chat slang handling</strong></li>
  <li>⚡ Implements both <strong>stemming</strong> and <strong>lemmatization</strong></li>
  <li>✅ Clean dataset ready for <strong>sentiment analysis, fake news detection, or ML models</strong></li>
</ul>

<hr>

<h2>🧠 How It Works</h2>

<ol>
  <li>Load the IMDB Dataset</li>
  <li>Normalize text → lowercase, remove HTML & URLs</li>
  <li>Clean text → remove punctuation, emojis, stopwords</li>
  <li>Expand short forms (e.g., OMG → Oh My God)</li>
  <li>Correct spelling errors using <code>TextBlob</code></li>
  <li>Tokenize text into sentences & words</li>
  <li>Apply stemming & lemmatization</li>
</ol>

<hr>

<h2>📂 Folder Structure</h2>

<pre>
data-preprocessing-cleaning/
├── Data_Preprocessing_and_Cleaning.ipynb   ← Main Notebook
├── IMDB Dataset.csv                        ← Raw Dataset
└── README.md                               ← Project Documentation
</pre>

<hr>

<h2>⚙️ Setup Instructions</h2>

<ol>
  <li>Clone the repository</li>
  
  <pre><code>git clone https://github.com/yourusername/data-preprocessing-cleaning</code></pre>

  <li>Install dependencies</li>

  <pre><code>pip install pandas textblob nltk emoji</code></pre>

  <li>Run the notebook in Google Colab or Jupyter</li>

  <pre><code>jupyter notebook Data_Preprocessing_and_Cleaning.ipynb</code></pre>
</ol>

<hr>

<h2>🧪 Sample Output</h2>

- Raw Input:  
  <code>"OMG!! Loved the movie 😂😂. It was AMAZING!!! Visit http://movielink.com"</code>  

- After Preprocessing:  
  <code>"oh my god loved the movie it was amazing"</code>  

<hr>

<h2>🙌 Credits</h2>

<p>
Created by <strong>Mehadi Hassan</strong> for text preprocessing and cleaning tasks in NLP pipelines.
</p>

<hr>

<p align="center">⭐ Star this repo if you find it useful for your NLP/ML projects!</p>
