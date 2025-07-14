# Sentimental_analysis
https://github.com/rinshasherin-hub/Sentimental_analysis.git
<pre>
```python
from textblob import TextBlob

text = input("Enter your sentence: ")
blob = TextBlob(text)
sentiment = blob.sentiment.polarity

if sentiment > 0:
    print("Sentiment: Positive")
elif sentiment < 0:
    print("Sentiment: Negative")
else:
    print("Sentiment: Neutral")
```
</pre>
