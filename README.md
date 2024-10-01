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
4. **General Cleaning**: Standardizes text, converts to lowercase, and filters out short or irrelevant sentences.

### Analysis Methods
1. **Demographic Analysis**: Using Meta Business Suite, we identified the age group, gender, and reach of Fieldseas’ audience. 
   - **Key Insight**: Fieldseas' audience is primarily middle-aged, with Facebook having a larger reach than Instagram.

2. **Network Analysis**: Using IG Exporter and Gephi, we analyzed the network of followers.
   - **Key Insight**: Identified potential collaborators like @Shiokeats.official and @Pullmansingaporeorchard from Instagram for future business partnerships.

3. **Sentiment Analysis**: Conducted using SAS Viya to determine positive, negative, or neutral sentiments around Wagyu beef.
   - **Key Insight**: General sentiment towards Wagyu beef is positive, especially around its marbling and tenderness.

4. **Topic Modelling**: AWS Comprehend was used to extract common themes discussed around Wagyu beef.
   - **Key Insight**: Popular topics include the premium quality of Wagyu beef, its sustainability, and cooking techniques.

### Tools and Libraries Used
- **Python Libraries**: `NLTK`, `re`, `pandas`, etc.
- **Data Scraping Tools**: Phantom Buster, Apify’s TikTok Scraper, IG Exporter
- **Network Analysis**: Gephi, NetworkX
- **Sentiment & Topic Modelling**: SAS Viya, AWS Comprehend

### Results
This analysis provides actionable insights into Fieldseas’ audience demographics, social media engagement, and customer sentiment. Recommendations are made to improve content strategy and increase engagement through targeted campaigns and collaborations.

