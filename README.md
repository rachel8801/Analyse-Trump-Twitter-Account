# Analyse-Trump-Twitter-Account
The goal of this project is to work with Twitter API to analyze tweets from a person, and in this case, President Donald Trump.
## Set up the notebook environment 
Follow the **SET UP** section
## Downloading the most recent tweets 
Twitter provides the API Tweepy (http://www.tweepy.org/) that makes it easy to access twitter content that is publicly available
## Warnining!!!
### Protect your Twitter Keys
If someone has your authentication keys, they can access your Twitter account and post as you! So don't give them to anyone,put your keys in `keys.json` for this assignment.
### Avoid making too many API calls.
Twitter limits developers to a certain rate of requests for data. If you make too many requests in a short period of time, you'll have to wait awhile (around 15 minutes) before you can make more. So carefully follow the code examples you see and don't rerun cells without thinking. Instead, always save the data you've collected to a file. We've provided templates to help you do that.
### Be careful about which functions you call!
This API can retweet tweets, follow and unfollow people, and modify your twitter settings. Be careful which functions you invoke! It is possible that you can accidentally re-tweet some tweets because you typed `retweet` instead of `retweet_count`.
