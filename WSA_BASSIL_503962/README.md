### Reddit Sentiment Analysis on ChatGPT Related Discussions

This project aims to analyze the sentiment of Reddit posts and comments related to ChatGPT. By examining the sentiment, we can gain insights into how users feel about ChatGPT, identify common themes, and understand public perception. The analysis involves extracting Reddit posts using the Reddit API, processing the text data, performing EDA (Exploratory Data Analysis), performing network analysis (graph creation, measures of centrality, community detection), and content analysis (specifically sentiment analysis).

## Setup

### Prerequisites
- Python 3.x
- Reddit API credentials (client ID, client secret, user agent, username, password)
- Required Python libraries

I have set up a JSON file called 'cred.json' that contains the credentials to the reddit API. 
The necessary python libraries to be installed to run the notebook without any missing importations are saved into a txt file called 'requirements.txt'. It can be installed by to your virtual environment by activating your environment in the terminal and using the command 'pip install -r PATH/TO/requirements.txt' to install them. The libraries are added without any versions to avoid possible conflicts.

Make sure to run the cells in order for the notebook to function correctly and avoid losing any variables.

### Data

Original Data: The data extracted from Reddit is saved in the folder data as a CSV file called 'data.csv'.
Processed Data: After pre-processing (data cleaning, tokenization, etc.), the dataset is saved as 'data_processed.csv' to avoid re-running the processing steps.
Relationships Data: The data of the relationships between the authors and commenters is stored in 'relationships_df.csv' for easy access during network analysis.

### More information

The notebook contains extensive explanations for each part as markdown cells. Additionally, you can refer to the notebook's Outline for a clearer understanding of the main categories and subcategories of the notebook's processing steps.