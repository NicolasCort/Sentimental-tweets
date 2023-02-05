# Sentimental Tweets

A sentiment analysis tool for tweets using machine learning algorithms




## Prerequisites

- Python 3.7 or later
- Tweepy (Python library for accessing the Twitter API)
- Textblob
- Transformes
- Torch



## Installation

Clone the repository to your local machine:

```bash
 git clone https://github.com/NicolasCort/Sentimental-tweets.git

```
Install the required packages using pip:

```bash
 pip install -r requirements.txt


```

## Usage

To use the sentiment analysis tool, you need to provide your Twitter API credentials. You can obtain these credentials by creating a Twitter Developer account and creating a new app.

```bash
consumer_key = "YOUR-CONSUMER-KEY"
consumer_secret = "YOUR-CONSUMER-SECRET"
access_token = "YOUR-ACCESS-TOKEN"
access_token_secret = "YOUR-ACCESS-TOKEN-SECRET"


```

To change the topic for the sentimental tweets you change the variable "q"

```bash
tweets = api.search(q="Ukraine", lang="en", count=100)

```



## License
This project is licensed under the [MIT License ](https://choosealicense.com/licenses/mit/) - see the LICENSE.md file for details.



