# Main Project Goal
The aim of this repository is to deliver real-time sentiment analysis on the latest cryptocurrency news.

## How?
### Step 1: Raw News Data Pipeline
We will establish a system to fetch raw news data multiple times a day, with the frequency to be determined. The sources for raw news data include:

- **RSS News Feeds**
- **Reddit:** Specifically from subreddits like Bitcoin, Ethereum, Solana, Cryptocurrency, News, and potentially others to be determined.
- **Google News API**

After pulling the news, we will immediately preprocess the text. The preprocessing steps are:

**Text Cleaning:**
- Remove special characters and numbers unless they are significant for sentiment.
- Convert all text to lowercase for uniformity.

**Tokenization:**
Split the text into individual words or tokens

**Stop Words Removal:**
Eliminate common words that do not contribute to sentiment or topic understanding, such as 'the', 'and', 'is', etc.

**Lemmatization:**
Convert words to their base or dictionary form (e.g., 'running' to 'run', 'buying' to 'buy') to standardize the vocabulary.
