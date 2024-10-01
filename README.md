# Social-Analytics-Project (Year 3 Sem 1) (2023)
## Project Overview
This project focuses on analyzing Fieldseas' social media data to provide business insights and propose strategies to increase customer engagement. We perform four key types of analysis: Demographic Analysis, Network Analysis, Sentiment Analysis, and Topic Modelling, utilizing data from social media platforms like Facebook, Instagram, TikTok, and Reddit.

### Dataset
We gathered data from Fieldseas' Meta Business Suite and scraped comments from relevant social media platforms using tools such as:
- **Meta Business Suite**: Provides data on audience demographics, post reach, and engagement.
- **IG Exporter**: Scraped the followers and followings of Fieldseas' Instagram account.
- **Phantom Buster**: Scraped comments related to Wagyu beef from Facebook, Instagram, and Reddit.
- **Apify's TikTok Scraper**: Extracted TikTok comments relevant to Wagyu beef in Singapore.

### Data Preprocessing
The preprocessing pipeline consists of:
1. **Lemmatization (NLTK)**: Ensures consistency by reducing words to their base form.
2. **Contraction Expansion (Python re module)**: Expands contractions like “don’t” to “do not”.
3. **Special Character Removal (Python re module)**: Removes emojis and special characters.
4. **General Cleaning**: Standardizes text, converts
