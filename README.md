# we-rate-dogs-wrangle-project
By Joy Mundia

## Dataset

> The wrangle project is based on dog ratings and data was sourced from Twitter. For
the project, three datasets were used which were subsequently merged to form one
dataframe. To execute the project, relevant libraries were imported such as pandas
and requests, but to mention a few.
The first dataset was manually downloaded from Udacity, Enhanced Twitter
Archive, which in the project goes by the term ‘archive’ for simplicity's sake. The file
was read using the pandas method of pd.read_csv.
The second data set is an image prediction dataset that was programmatically
downloaded and read as image_pred.
The final dataset was downloaded manually from udacity, tweet-json.txt. Due to
mobile verification issues, the data was not accessed from the Twitter API. The data
was loaded and saved as df_api.

## Summary of Findings

> The vast majority of dogs got a rating greater than 10 out of 10, with the largest proportion earning a 12 out of 10 rating. The highest and lowest ratings were 14 and 8 respectively. The most popular dog stage was the pupper dog stage and the least popular was floofer. The retrievers were among the favourite, with the Golden retriever being the most favourite and Labrador following in second place. Great correlation was established between favourite count and retweet count.

## Key Insights for Presentation

> To ensure accurate data insights, the data quality and tidiness issues were tackled systematically, and redundant columns were dropped. Visualizations of retweet and favourite were displayed to show the great correlation.
