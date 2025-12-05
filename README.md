# Assignment_3
Course: Collecting Data | Student Number: S6494935

### 1. Corpus
The corpus consists of 1 CSV file, which contains 3 columns:
| Column Name | Description |
| :--- | :--- |
| title | The title of the news article. |
| link | The link to the news article.  |
| news_source | The news source that published the news article. |

### 2. Scraped Data
The data consists of news articles visible on Google News, that can be found under the U.S. topic webpage.

### 3. Cleaning of the Data
The first 2 rows only contain links, but no title nor news source. I have therefore removed those first 2 rows.

### 4. Format of the Files in the Corpus
The corpus is in CSV format.

### 5. Robots.txt file
The robots.txt file contains the following:
```
User-agent: *
Allow: /topics/
```
Based on that, I inferred that it is legal for me to scrape the news articles under the U.S. topic, considering the url to that page is as follows: https://news.google.com/topics/CAAqIggKIhxDQkFTRHdvSkwyMHZNRGxqTjNjd0VnSmxiaWdBUAE?hl=en-US&gl=US&ceid=US%3Aen